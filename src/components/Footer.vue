<template>

<footer class="position-relative home-footer px-sm-5 py-3">
  <div class="footer_style">

<div class="d-flex justify-content-between pb-3 footer-top-row">
<div class="mt-2">
<img src="/assets/MYM.png">
</div>
<!-- <div class="scroll-top"><a href="#header" class="d-flex align-items-center">SCROLL TO TOP <i class="ms-3 fa fa-chevron-up"></i></a></div> -->
<div class="d-flex app-link">
<a href="" class="me-3"><img class="download-apple" src="/assets/AppleStr.png" style="max-width: 190px"></a>
<a href=""><img class="download-app" src="/assets/AndStore.png" style="max-width: 190px"></a>
</div>
</div>

<div class="row m-0 position-relative footer-menu">
<div class="container p-0">
<div class="row m-0">
<div class="col-sm-12 p-sm-0">
<div class="row m-0 position-relative">
<div class="col-sm-3 col-6">
<p class="heading theme-black-text mb-3">General</p>

<p class="mb-0"><a href="">Shipping Calculator</a></p>


<p class="mb-0"><a href="">Restricted Items</a></p>


<p class="mb-0"><a href="">Rate Sheet</a></p>

</div>
<div class="col-sm-3 col-6">
<p class="heading theme-black-text mb-3">Help</p>

<p class="mb-0"><a href="">Shipping Calculator</a></p>


<p class="mb-0"><a href="">FAQ</a></p>


<p class="mb-0"><a href="">About Us</a></p>


<p class="mb-0"><a href="">Contact Us</a></p>


<p class="mb-0"><a href="">Location</a></p>


<p class="mb-0"><a href="">Opening Hours</a></p>

</div>
<div class="col-sm-3 col-6">
<p class="heading theme-black-text mb-3">Customer Service</p>

<p class="mb-0"><a href="">Shipping Calculator</a></p>


<p class="mb-0"><a href="">My Account</a></p>

</div>
<div class="col-sm-3 col-6">
<p class="heading theme-black-text mb-3">Contact Us</p>

<p class="mb-0"><a href=""><i class="fa fa-envelope me-2"></i> support@airdropja.com</a></p>


<p class="mb-0"><a href=""><i class="fa fa-phone me-2"></i> +1-876-627-1894</a></p>


<p class="mb-0"><a href=""><i class="fa fa-whatsapp me-2"></i> +1-876-554-5265</a></p>

</div>
</div>
</div>
</div>
</div>
</div>
<div class="row m-0 position-relative footer-bottom mt-1 social-ic">

<div class="col-sm-9 d-flex align-items-left">
<p style="opacity: 1">© 2021 Airdrop Limited. All rights Reserved. Terms and Conditions. Privacy Policy</p>
</div>
<div class="col-sm-3">
<p class="heading theme-black-text">Follow Us</p>
<a href="" class="me-3"><i class="fa fa-facebook"></i></a>
<a href="" class="mx-3"><i class="fa fa-twitter"></i></a>
<a href="" class="mx-3"><i class="fa fa-instagram"></i></a>
<a href="" class="mx-3"><i class="fa fa-youtube"></i></a>
</div>
</div>
<!-- <img src="img/footer-text-1.svg" class="footer-texture">
<img src="img/footer-text-2.svg" class="footer-texture"> -->

</div>

</footer>

</template>

<script>
export default {
    
}
</script>

<style scoped>

.home-footer 
{
background:white;
}

.footer-top-row 
{
/* border-bottom: 1px solid  #1F4F46!important;  */
}

.footer-menu 
{
padding: 2rem 0;
z-index: 999;
}

.position-relative 
{
position: relative!important;
}

.home-footer p 
{
color: #1F4F46!important;
font-size: 18px;
width: 100%;
float: left;
}

.footer-menu p a
{
color:#1F4F46!important;

float: left;
}

.footer-menu p a:hover 
{
color: #1F4F46;
text-decoration: none;
opacity: 1;
}
.footer-menu p a:hover::after {
width: 100%;
}
.footer-menu p a::after {
content: '';
height: 1px;
width: 0;
border-radius: 25px;
display: block;
position: relative;
left: 0;
bottom: 3px;
transition: all .4s ease;
background-color:#1F4F46!important;
}
.social-ic {
z-index: 9;
}
.social-ic a i {
color:  #1F4F46!important;
font-size: 1.5rem;
}


.footer_style
{
    padding-right: 2rem !important;
    padding-left: 2rem !important;
}

.download-apple
{
    max-width: 160px !important;
    margin-top: 6px;
}




/* 
.single-cta {
    float: left;
    width: 100%;
    text-align: left;
    line-height: 45px;
    margin-top: 3px;
}
ul {
    margin: 0px;
    padding: 0px;
}
.footer-section {
  background: white;
  position: relative;
      border-top: 1px solid #efefef;
      margin-top: 20px;
}
.footer-cta {
  border-bottom: 1px solid #378475;
}
.single-cta i {
  color: #378475;
  font-size: 30px;
  float: left;
  margin-top: 8px;
}
.cta-text {
  padding-left: 15px;
  display: inline-block;
}
.cta-text h4 {
  color: #378475;
  font-size: 20px;
  font-weight: 600;
  margin-bottom: 2px;
}
.cta-text span {
  color: #757575;
  font-size: 15px;
}
.footer-content {
  position: relative;
  z-index: 2;
}
.footer-pattern img {
  position: absolute;
  top: 0;
  left: 0;
  height: 330px;
  background-size: cover;
  background-position: 100% 100%;
}
.footer-logo {
  margin-bottom: 30px;
}
.footer-logo img {
    max-width: 200px;
}
.footer-text p {
  margin-bottom: 14px;
  font-size: 14px;
      color: #7e7e7e;
  line-height: 28px;
}
.footer-social-icon span {
  color: #fff;
  display: block;
  font-size: 20px;
  font-weight: 700;
  font-family: 'Poppins', sans-serif;
  margin-bottom: 20px;
}
.footer-social-icon a {
  color: #fff;
  font-size: 16px;
  margin-right: 15px;
}
.footer-social-icon i {
  height: 40px;
  width: 40px;
  text-align: center;
  line-height: 38px;
  border-radius: 50%;
}
.facebook-bg{
  background: #3B5998;
}
.twitter-bg{
  background: #55ACEE;
}
.google-bg{
  background: #DD4B39;
}
.footer-widget-heading h3 {
  color: #378475;
  font-size: 20px;
  font-weight: 600;
  margin-bottom: 40px;
  position: relative;
  text-align: left;
}
.footer-widget-heading h3::before {
  content: "";
  position: absolute;
  left: 0;
  bottom: -15px;
  height: 2px;
  width: 50px;
  background: #378475;
}
.footer-widget ul li {
  display: inline-block;
  float: left;
  width: 50%;
  margin-bottom: 12px;
  text-align: left;
}
.footer-widget ul li a:hover{
  color: #378475;
}
.footer-widget ul li a {
  color: #878787;
  text-transform: capitalize;
  text-align: left;
}
.subscribe-form {
  position: relative;
  overflow: hidden;
}
.subscribe-form input {
  width: 100%;
  padding: 14px 28px;
  background: #2E2E2E;
  border: 1px solid #2E2E2E;
  color: #fff;
}
.subscribe-form button {
    position: absolute;
    right: 0;
    background: #378475;
    padding: 14px 20px;
    border: 1px solid #378475;
    top: 0;
}
.subscribe-form button i {
  color: #fff;
  font-size: 22px;
  transform: rotate(-6deg);
}
.copyright-area{
  background: #1F4F46;
  padding: 25px 0;
}
.copyright-text p {
  margin: 0;
  font-size: 14px;
  color: #878787;
}
.copyright-text p a{
  color: #378475;
}
.footer-menu li {
  display: inline-block;
  margin-left: 20px;
}
.footer-menu li:hover a{
  color: #378475;
}
.footer-menu li a {
  font-size: 14px;
  color: #878787;
}

.text_clr
{
color: #378475;
}


.foot_txt
{

color: ;
} */


@media (min-width:1200px) and (max-width: 2000px) 
{


}

@media (min-width:992px) and (max-width: 1199px) 
{


}

@media (min-width:768px) and (max-width: 991px) 
{



}


@media (min-width:576px) and (max-width: 767px) 
{

}


@media (min-width:320px) and (max-width: 575px) 
{



  
}

</style>

