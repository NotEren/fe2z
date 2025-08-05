<style>p {
    margin-top: 0;
    margin-bottom: 1rem;
    color: white  !important;
}



@import url("https://fonts.googleapis.com/css2?family=Cairo:wght@200;300;400;500;600;700;800;900;1000&display=swap");

:root {
    --cbtn: #1b1b1c !important;
}

* {
    font-family: Cairo, sans-serif !important;
}

        .navbar-toggler.collapsed .feather-menu {
            color: white!important;
            stroke: white!important;
        }


a[href=Apps][style*="--cbtn"] {
    --cbtn: white !important;
}

@keyframes float {
    0% {
        transform: translateY(0px);
    }
    50% {
        transform: translateY(-20px);
    }
    100% {
        transform: translateY(0px);
    }
}

@keyframes shadeanm {
    0% {
        box-shadow: 0 5px 15px 0 rgba(0, 0, 0, .6);
    }
    50% {
        box-shadow: 0 15px 15px 0 rgba(0, 0, 0, .2);
    }
    100% {
        box-shadow: 0 5px 15px 0 rgba(0, 0, 0, .6);
    }
}


.img1 {
    width: 50%;
    animation: slideAnimation 1s infinite alternate;
}

@keyframes slideAnimation {
    from {
        transform: translateY(0);
    }
    to {
        transform: translateY(20px); 
    }
}

.form-control {
    background-color: #b60000;
}

.feather-menu {
    color: #5a56f5 !important;
}
.bg-white.py-10 {
  display: none !important;
}
#myCenterElement {
  display: none;
}


.rounded-pill {
    position: relative;
    padding: 200px 25px;
    background-color: #5a56f5 !important;
    border: none;
    color: white;
    font-size: 16px;
    cursor: pointer;
    transition: transform 0.2s ease-in-out;
    padding: 0.75rem 1.25rem !important;
    overflow: hidden;
    animation: rotate 3s infinite linear;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.rounded-pill::before {
    content: "";
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
    height: 100%;
    opacity: 0;
    border-radius: 50%;
    pointer-events: none;
    animation: rotate 3s infinite linear;
}

.rounded-pill:hover {
    transform: scale(1.1);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
}


@media screen and (max-width: 900px) {
    .img1 {
        width: 100%;
    }
}

::selection {
    background-color: #5a56f5;
    color: #5a56f5;
}

.icon-stack {
    animation: float 4s ease-in-out infinite, shadeanm 4s ease-in-out infinite;
}

table {
    border-collapse: collapse;
    width: 80%;
    margin: auto;
}

td {
    border: 1px solid #ccc;
    padding: 10px;
    text-align: center;
}

#set-lang {
    background-color: transparent;
    color: white !important;
    border: 1px solid white !important;
}

#set-lang option {
    background-color: black !important;
    color: white !important;
}

.custom-img {
    width: 100px;
    height: 100px;
}

.boxmseg {
    background-color: transparent;
}

input[type=search].form-control.mb-1 {
    background: 0;
}

.white-icon img {
    filter: brightness(0) invert(1);
}

button.btn.btn-primary.btn-marketing.text-center {
    background-color: transparent !important;
}

.col-6 {
    display: flex;
    justify-content: center;
    margin: 0 auto;
}

.image-container {
    border: 3px solid #5a56f5;
    border-radius: 1.5rem;
    box-shadow: 1px 1px 1px #5a56f5, 0 0 10px #5a56f5, 0 0 2px #5a56f5;
}

.row {
    display: flex;
    flex-wrap: wrap;
}

.col-6 {
    width: 20%;
}

.text-uppercase-expanded {
    color: #ffffff;
    text-transform: uppercase;
    font-size: 30em;
    font-weight: 700;
    display: flex;
    align-items: center;
    justify-content: center;
}

.text-uppercase-expanded svg {
    color: #ffffff;
    width: 1.5em;
    height: 1.5em;
    margin-left: 2px;
}

.card-img-top.shop-img {
    border-color: #5a56f5 !important;
    background-clip: border-box;
    border: 2px solid #5a56f5;
    border-radius: 3rem;
    box-shadow: 1px 1px 1px #5a56f5 , 0 0 10px #5a56f5, 0 0 2px #5a56f5;
}

.sol {
    display: flex;
    justify-content: center;
    align-items: center;
}

.sol a {
    display: inline-block;
    margin: 0 5px;
    padding: 5px;
    transform-origin: center;
    animation: floatupdown 3s ease-in-out infinite;
}

@keyframes floatupdown {
    0%, 100% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-10px);
    }
}

.navbar-nav li,
.navbar-nav a,
.navbar-nav select {
    color: ffffff  !important;
    text-align: center;
}

.text-light {
    color: #0e1017!important;
}

.form-control {
    color: #5a56f5 !important;
    background-color: #0e1017;
}

.form-control::placeholder {
    color: #5a56f5!important;
}

.form-control.rounded-pill {
    background: linear-gradient(to top, #5a56f50%, #b60000 100%) !important;
    border: 1px solid #5a56f5!important;
    box-shadow: 1px 1px 1px #b60000, 0 0 10px #b60000, 0 0 2px #b60000;
    border-radius: 24px;
}

.btn.btn-primary.btn-marketing.rounded-pill.btn-home,
.badge.badge-light.badge-pill.badge-marketing.badge-sm,
.btn.btn-primary.btn-marketing.rounded-pill,
.cc,
.page-header-title,
.navbar-toggler.collapsed,
.btn-primary.btn.rounded-pill.px-4,
.list-unstyled.mb-0,
.typing-demo,
.text-arrow-icon.small,
.card-title.small.mb-0,
.text-dark,
.package_model,
.card-title,
.badge.badge-apps {
    text-transform: uppercase;
    background-image: linear-gradient(-225deg, #5a56f5 0%, #ffffff 29%, #5a56f5 100%, #5a56f5 60%);
    background-size: auto auto;
    background-clip: border-box;
    background-size: 200% auto;
    color: #5a56f5;
    background-clip: text;
    text-fill-color: transparent;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: textclip 2s linear infinite;
    display: inline-block;
    text-align: center;
}

@keyframes textclip {
    to {
        background-position: 200% center;
    }
}

.card-text {
    color: #ffffff !important;
}

.msg,
h1.mb-4 {
    color: #ffffff !important
}

.msg p {
    background: #5a56f5 !important;
    padding: 10px;
    border-radius: 7px;
    margin-top: 10px;
}

.wrapper {
    display: grid;
    place-items: center;
}

.typing-demo {
    width: 22ch;
    animation: typing 2s steps(22), blink .5s step-end infinite alternate;
    white-space: nowrap;
    overflow: hidden;
    border-right: 3px solid;
    font-family: monospace;
    font-size: 2em;
}

@keyframes typing {
    from {
        width: 0;
    }
}

@keyframes blink {
    50% {
        border-color: transparent;
    }
}




.col-lg-6.col-md-6.mb-5.mb-lg-0 {
    text-align: center;
}

.svg-border-waves.text-white {
    display: none;
}

.icon-stack.icon-stack-xl.bg-gradient-primary-to-secondary.text-white.mb-4 {
    background: linear-gradient(to top, #5a56f5 0%, #5a56f5 100%) !important;
}

.d-flex.align-items-center.justify-content-between.mb-3 {
    display: none !important;
}

.page-header-dark {
    color: #5a56f5;
    background: linear-gradient(to top, #5a56f5 0%, #5a56f54f 100%) !important;
}


.bg-light {
    background-color: #0e1017 !important;
}

.navbar-light .navbar-nav .nav-link:hover,
.navbar-light .navbar-nav .nav-link:focus {
    color: #ffffff;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
    margin-bottom: .5rem;
    font-weight: 500;
    line-height: 1.2;
    color: #ffffff;
}

.text-white {
    color: #0e1017 !important;
}

.bg-white {
    background-color: #0e1017 !important;
}

.navbar-marketing .navbar-brand {
    font-size: 0;
    color: #5a56f5!important;
    font-family: var(--cfont) !important;
}

body {
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #5a56f5;
    text-align: right;
    background-color: #0e1017;
}

.modal-body {
    margin: 0;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #5a56f5;
    text-align: right;
    background-color: #0e1017;
}

.navbar-light .navbar-toggler {
    color: #ffffff;
    border-color: rgb(255 255 255 / 10%);
}

.navbar-light .navbar-nav .nav-link {
    color: #ffffff;
}

.text-white-50,
.page-header-dark .page-header-text {
    color: #5a56f5 !important;
}

.badge-light {
    color: #5a56f5;
    background-color: #0e1017;
}

.bg-dark {
    background-color: #0e1017 !important;
}

.card {
    background-image: url !important;
    background-size: cover;
    position: relative;
    display: -webkit-box;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    flex-direction: column;
    min-width: 0;
    word-wrap: break-word;
    background-color: #0e1017;
    border-color: #5a56f5 !important;
    background-clip: border-box;
    border: 3px solid #5a56f5;
    border-radius: 1.5rem;
    box-shadow: 1px 1px 1px #5a56f5, 0 0 10px #5a56f5, 0 0 2px #5a56f5;
}

.iconWeb.cc {
    border-color: #5a56f5 !important;
    background-clip: border-box;
    box-shadow: 1px 1px 1px #5a56f5, 0 0 10px #5a56f5, 0 0 2px #5a56f5;
}

.badge-light {
    color: #5a56f5;
    background-color: #5a56f5;
    box-shadow: 1px 1px 1px #5a56f5, 0 0 10px #5a56f5, 0 0 2px #5a56f5;
}

.text-dark,
.page-header-light .btn-link {
    color: #5a56f5 !important;
}

.pricing .pricing-price {
    font-size: 3rem;
    color: #ffffff;
    margin-bottom: 1rem;
}

hr {
    margin-top: 0;
    margin-bottom: 1rem;
    border: 0;
    border-top: 1px solid rgb(0 0 0 / 0%);
}

.pb-10,
.py-10 {
    padding-bottom: 0 !important;
}

.svg-border-wave {
    padding-top: 0;
}

.page-header {
    position: relative;
    padding-top: 2rem;
    padding-bottom: 6rem;
}

.navbar-marketing {
    -webkit-transition: background-color .15s ease-in-out;
    transition: background-color .15s ease-in-out;
    padding-top: .5rem;
    padding-bottom: .5rem;
    width: 100% !important;
}

.pt-5,
.py-5 {
    padding-top: 2rem !important;
}

.icon-stack {
    box-shadow: 1px 1px 1px #5a56f5, 0 0 10px #5a56f5, 0 0 2px #5a56f5;
}

.btn-primary {
    box-shadow: 1px 1px 1px #5a56f5, 0 0 10px #5a56f5, 0 0 2px #5a56f5;
    border-radius: 24px;
}

.msg {
    padding: 10px;
    margin-bottom: 15px;
    border-radius: 4px;
    margin-top: -12px;
    background: #5a56f5;
    border: 1px solid #5a56f5;
}

element.style {
    border-radius: 10px;
}

h3,
.h3 {
    font-size: 1.4rem;
    color: #5a56f5;
}

.card.pricing.h-100 {
    width: 100%;
    height: 100px;
    background: #ffffff;
    position: relative;
    display: flex;
    place-content: center;
    place-items: center;
    overflow: hidden;
    border-radius: 20px;
color:white !important;
    margin: 10px 0;
}


.card.pricing.h-100 div {
    z-index: 1;
color:white !important;
}

.card.pricing.h-100:before {
    content: "";
    position: absolute;
    width: 350px;
    background: #ffffff;
  color:white !important;
    animation: rotbgimg 3s linear infinite;
    transition: all .2s linear;
}

@keyframes rotbgimg {
    from {
        transform: rotate(0deg);
    }
    to {
        transform: rotate(360deg);
    }
}



.text-arrow-icon.small {
    color: #ffffff !important;
    height: auto;
}

.col-lg-3.col-md-6.mb-5.mb-lg-0 {
    text-align: center;
}

.text-xs.text-gray-500 {
    color: #ffffff !important;
}

.card-flag.card-flag-dark.card-flag-top-right.card-flag-lg {
    background-color: #5a56f5 !important;
}

.navbar-nav.ml-auto.mr-lg-5 {
    text-align: center;
}

.row.align-items-center {
    text-align: center !important;
}

.page-header-dark {
    color: #ffffff;
    background: linear-gradient(to top, #3f5a77 0%, #101723 100%) !important;
}

.svg-inline--fa.fa-check-circle.fa-w-16.text-teal {
    color: #ffffff !important;
}

.svg-border-waves.text-white {
    display: none;
}

.backgroundHome {
    background-image: url() !important;
    background-repeat: no-repeat;
    background-size: cover !important;
    background-position: bottom center, 100%, 100% !important;
}



.card-body.p-5 {
    background: #00000000 !important;
}

.card.pricing.h-100 {
  background-color: #00000013 !important;
  color: white !important;
  background-image: url(https://raw.githubusercontent.com/NotEren/fe2z/970c8cfec6ef48e1a6136d21fe24d54785bf7628/13_modified.svg) !important;
  border-radius: 1.5rem;
  animation: glowingBorder 1.5s infinite;
  transition: box-shadow 0.3s ease-in-out;
  border: 3px solid transparent;
}

/* تأثير الحواف المتوهجة الثابتة - اللون #5a56f5 */
@keyframes glowingBorder {
  0% {
    box-shadow: 0 0 15px rgba(90, 86, 245, 0.6),
                0 0 30px rgba(90, 86, 245, 0.5),
                0 0 60px rgba(90, 86, 245, 0.4),
                0 0 100px rgba(90, 86, 245, 0.3);
  }
  50% {
    box-shadow: 0 0 30px rgba(120, 116, 255, 0.5),
                0 0 60px rgba(90, 86, 245, 0.4),
                0 0 90px rgba(120, 116, 255, 0.3),
                0 0 120px rgba(90, 86, 245, 0.3);
  }
  100% {
    box-shadow: 0 0 15px rgba(90, 86, 245, 0.6),
                0 0 30px rgba(90, 86, 245, 0.5),
                0 0 60px rgba(90, 86, 245, 0.4),
                0 0 100px rgba(90, 86, 245, 0.3);
  }
}





.card-footer {
    display: none;
}

.btn.btn-primary.btn-marketing.rounded-pill {
    background-color: #00000013 !important;

}

.btn.btn-primary.text-center.btn-Shop {
    background-color: #00000013 !important;
}

.card-flag.card-flag-dark.card-flag-top-right.card-flag-lg {
    background-color: #5a56f5 !important;
}

.text-uppercase-expanded.text-xs.mb-4 {
    background-color: #5a56f5 !important;
}

.msg_top {
    background-color: #0e1017 !important;
}

.mb-1 {
    color: #ffffff !important;
    height: auto;
}

.zoomIn {
    -webkit-animation-name: zoomin;
    animation-name: zoomin;
}

@-webkit-keyframes zoomin {
    from {
        opacity: 0;
        -webkit-transform: scale3d(.3, .3, .3);
        transform: scale3d(.3, .3, .3);
    }
    50% {
        opacity: 1;
    }
}

@keyframes zoomin {
    from {
        opacity: 0;
        -webkit-transform: scale3d(.3, .3, .3);
        transform: scale3d(.3, .3, .3);
    }
    50% {
        opacity: 1;
    }
}

.card-img-top.StorePay-img {
    object-fit: cover;
    height: auto;
    width: auto;
    border-radius: 1.5rem 1.5rem 0 0;
}
.card.pricing.h-100 div h2 {
    z-index: 1;
    color:white !important;
}







.footer.footer-dark {
  background-image: url(https://raw.githubusercontent.com/NotEren/fe2z/970c8cfec6ef48e1a6136d21fe24d54785bf7628/13_modified.svg) !important;
  background-repeat: no-repeat;
  background-size: cover !important;
  background-position: bottom center, 100%, 100% !important;




}

.backgroundHome {
  background-image: url(https://drstore.net/caf/morfn.svg) !important;
  background-repeat: no-repeat;
  background-size: cover !important;
  background-position: bottom center, 100%, 100% !important;
}

.boxmseg {

  background-image: url(https://zain-ae.com/hero.svg) !important;
  background-repeat: no-repeat;
  background-size: cover !important;
  background-position: bottom center, 100%, 100% !important;

}


}
  }
  
  

  

  
  
  
  
  
  }

  
  }
  
 
 
 
  

  
  
  

  
  
  }
  

 
  }
  
 
  
  
  }
  }
  
  
 
  }
  
  
  }
  
  @keyframes rotBGimg {
    from {
      transform: rotate(0deg);
    }
  
    to {
      transform: rotate(360deg);
    }
  }
  
  .card.pricing.h-100::after {
    content: '';
    position: absolute;
    background-size: cover;
    inset: 5px;
    border-radius: 15px;
  }
  
  /* end card.pricing.h-100s header */
  
  
  .text-arrow-icon.small {
    height: auto
  }
  
  .col-lg-3.col-md-6.mb-5.mb-lg-0 {
    text-align: center;
  }
  
  .text-xs.text-gray-500 {
    color: #ffffff !important;
  }
  
  .card-flag card-flag-dark card-flag-top-right card-flag-lg {
    background-color: #7431cf !important;
  }
  
  .navbar-nav.ml-auto.mr-lg-5 {
    text-align: center;
  }
  
  
  .row.align-items-center {
    text-align: center !important;
  }
  
  
  .page-header-dark {
    color: #fff;
    background: linear-gradient(to top, #7431cf 0%, #091427 100%) !important;
  
  }
  
  .svg-inline--fa.fa-check-circle.fa-w-16.text-teal {
    color: #fff !important;
  
  }
  
  .svg-border-waves.text-white {
    display: none;
  }
  
  .backgroundHome {
    background-image: url(https://raw.githubusercontent.com/NotEren/fe2z/970c8cfec6ef48e1a6136d21fe24d54785bf7628/13_modified.svg) !important;
    background-repeat: no-repeat;
    background-size: cover !important;
    background-position: bottom center, 100%, 100% !important;
  }
  
  .navbar.navbar-marketing.navbar-expand-lg.bg-white navbar-light.animate_animated.animate_fadeInDown {
    background-image: url(https://raw.githubusercontent.com/NotEren/fe2z/a589867e27e72f93d229b85148a2fb0dc31ecf70/13_modified.svg) !important;
    background-repeat: no-repeat;
    background-size: cover !important;
    background-position: bottom center, 100%, 100% !important;
  
  }
  
  
  .card-body.p-5 {
    background: #09142700 !important;
  
  
  }
  
  .card-body.p-3 {
    background-image: url(https://raw.githubusercontent.com/NotEren/fe2z/a589867e27e72f93d229b85148a2fb0dc31ecf70/13_modified.svg) !important;
    background-repeat: no-repeat;
    background-size: cover !important;
  
  }
  
  .card-body {
    background-image: url(https://raw.githubusercontent.com/NotEren/fe2z/a589867e27e72f93d229b85148a2fb0dc31ecf70/13_modified.svg) !important;
    background-repeat: no-repeat;
    background-size: cover !important;
  
  }
  
  
  .card.pricing.h-100 {background-color: #09142713 !important;
  }
  
  
  .footer.footer-dark {
    background-image: url(https://raw.githubusercontent.com/NotEren/fe2z/a589867e27e72f93d229b85148a2fb0dc31ecf70/13_modified.svg) !important;
    background-repeat: no-repeat;
    background-size: cover !important;


  
</style>
