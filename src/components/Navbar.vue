<template>

<div class="fixed-top nav_bg">
<div class="container">
    <div class="row">
      <div class="col-auto">
         <div class="logo-m">
          <a href=""> <img class="logo_style" alt="Vue logo" src="/assets/Salada.png"></a>
         </div>
    </div>
  <div class="col">
  <nav class="navstyle navbar navbar-expand-lg navbar-light shift">
  <div class="container pe-0">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="true" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="navbar-collapse" id="navbarSupportedContent">
    
      <ul class="navbar-nav nav_styel mb-8 mb-lg-0">

        <!-- <li class="nav-item nav-l-s">   
          <a class="navbar-brand" href="#">
          </a>
        </li> -->
                   
        <li class="nav-item nav-l-s">                       
           <a class="nav-link " aria-current="page" href="#firstsection"> Home </a>
        </li>

        <li class="nav-item nav-l-s">                       
           <a class="nav-link" aria-current="page" href="#featuresection"> How it works</a>
        </li>

        <li class="nav-item nav-l-s">
        <a class="nav-link" aria-current="page"  href="#video"> Video </a>
        </li>

        <li class="nav-item nav-l-s">
        <a class="nav-link" aria-current="page" href="#support"> Support </a>
        </li>
     
        <li class="nav-item nav-l-s">
        <a class="nav-link" aria-current="page" href="#pricing"> Pricing  </a>
        </li>
      
        <li class="nav-item nav-l-s">
        <a class="nav-link" aria-current="page" href="#news"> News  </a>
        </li>
         
    
        <li class="nav-item icon_style">
        <a href="#"><div class="login-btn btn"><i class="fa fa-user"></i> Login</div></a>
         <a href="#"><div class="signup-btn btn"><i class="fa fa-user"></i> Sign Up </div></a>
        </li>
      </ul>

    </div>
  </div>
  </nav>
      </div>
    </div>
   

</div>
</div>

</template>

<script>

export default {
 name: "Navbar",
};


</script>

<style scoped>
nav ul li.nav-l-s ,
nav ul li.nav-l-s:after,
nav ul li.nav-l-s:before {
  transition: all .5s;
}


.nav_bg
{
 background-color: white;
}
.navstyle
{
    background-color: white;
    /* box-shadow: 0px 4px 15px -1px rgb(182, 182, 182); */
}
.login-btn.btn {
-webkit-appearance: none;
-moz-appearance: none;
appearance: none;
background-color: #fff!important;
cursor: pointer;
font-size: 1rem;
padding: 8px 25px;
text-align: center;
text-transform: uppercase;
margin-top: 2px;
color: #1F4F46;
border-radius: 50px;
transition: 0.7s;
box-shadow: 0px 0px 9.49px -0.49px rgb(40 40 40 / 20%);
font-weight: 300;
}


.signup-btn.btn {
-webkit-appearance: none;
-moz-appearance: none;
appearance: none;
background: linear-gradient(90deg, #1F4F46 5%, #55c0ab 190%);
cursor: pointer;
font-size: 1rem;
padding: 8px 25px;
text-align: center;
text-transform: uppercase;
margin-top: 2px;
color: white;
border-radius: 50px;
transition: 0.7s;
box-shadow: 0px 0px 9.49px -0.49px rgb(40 40 40 / 20%);
font-weight: 300;
}


.login-btn.btn:hover {
background: linear-gradient(90deg, #1F4F46 5%, #55c0ab 190%);
color: #fff!important;
}

.signup-btn.btn:hover{
 
background: linear-gradient(90deg, #ffffff 5%, #ffffff 190%);
color: #1F4F46!important;

}

.login-btn.btn:hover, .login-btn.btn:focus {
color: #fff;
outline: 0;
}
.navsec_style
{
  padding-left: 480px;
}

.icon_style
{
    margin-top: 10px;
    margin-bottom: 10px;
}

.txt_style
{
 text-shadow: black;
 box-shadow: black 3px solid; 
}

.logo_style
{ 
 max-height: 93px;
 max-width: 80px;
 margin-top: 18px;

}

.nav_styel
{
margin-left: auto;
}
.shift ul li a {
    padding: 18px 20px 12px!important;
}
.shift ul li:last-child a {
    padding: 0 0 0 26px !important;
}
nav.navstyle {
    padding: 0;
}
.shift ul li.nav-l-s {
  position:relative;
  z-index: 1;
}
.shift ul li.nav-l-s a:hover {
  color: #1f4f46 !important;
  
}
.shift ul li.nav-l-s:after {
    content: '';
    height: 3px;
    width: 0;
    border-radius: 25px;
    display: block;
    position: relative;
    left: 0;
    bottom: -3px;
    transition: all .4s ease;
    background-color: #1f4f46;

}
.shift ul li.nav-l-s:hover:after {
    width: 100%;
}


@media (min-width: 1504px) and (max-width: 2000px)
{

}



@media (min-width: 1200px) and (max-width: 1503px)
{
}



@media (min-width: 992px) and (max-width: 1999px)
{
.shift ul li a
{
  padding: 18px 8px 12px!important;
}


}


@media (min-width: 768px) and (max-width: 991px) 
{


.navbar-toggler
{
    margin-top: 6px !important;
    margin-left: auto !important;
    margin-bottom: 10px !important;
}


}


@media (min-width: 576px) and (max-width: 767px) 
{


.navbar-toggler
{
    margin-top: 6px !important;
    margin-left: 308px !important;
    margin-bottom: 6px !important;
}

}


@media (min-width: 320px) and (max-width: 575px) 
{

  .navbar-toggler
{
    margin-top: 6px !important;
    margin-left: auto;
    margin-bottom: 6px !important;
}




}

</style>