<template>
<div>
<nav class="navstyle navbar navbar-expand-lg navbar-light stroke">
  <div class="container">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
       <img class="logo_style" alt="Vue logo" src="/assets/Salada.png">
      <ul class="navbar-nav nav_styel mb-8 mb-lg-0">

        <li class="nav-item">   
          <a class="navbar-brand" href="#">
          </a>
        </li>
                   
        <li class="nav-item">                       
           <a class="nav-link " aria-current="page" href="#firstsection"> Home </a>
        </li>

        <li class="nav-item">                       
           <a class="nav-link" aria-current="page" href="#featuresection"> How it works</a>
        </li>

        <li class="nav-item">
        <a class="nav-link" aria-current="page"  href="#"> About Us </a>
        </li>

        <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#"> Video </a>
        </li>
     
        <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#"> Pricing  </a>
        </li>
      
        <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#"> News  </a>
        </li>
         
         

        <li class="nav-item icon_style">
        <i class="fa fa-user" aria-hidden="true"></i>
        </li>
        
    
        <!-- <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li> -->
        <!-- <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li> -->
      </ul>
      <!-- <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form> -->
    </div>
  </div>
</nav>
</div>
</template>

<script>
export default {
 name: "Navbar",
};
</script>

<style scoped>

.navstyle
{
    background-color: white;
}

.navsec_style
{
  padding-left: 480px;
}

.icon_style
{
  margin-top: 8px;
  /* padding-left: 10px; */
}

.txt_style
{
 text-shadow: black;
 box-shadow: black 3px solid; 
}

.logo_style
{ 
 max-height: 60px;
 max-width: 60px;
 /* margin-left: 250px; */
}


.nav_styel
{
margin-left: auto;
}


nav.stroke ul li a,
nav.fill ul li a {
  position: relative;
}
nav.stroke ul li a:after,
nav.fill ul li a:after {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
  width: 0%;
  content: '.';
  color: transparent;
  background: #aaa;
  height: 1px;
}
nav.stroke ul li a:hover:after {
  width: 100%;
}

nav.fill ul li a {
  transition: all 2s;
}

nav.fill ul li a:after {
  text-align: left;
  content: '.';
  margin: 0;
  opacity: 0;
}
nav.fill ul li a:hover {
  color: #fff;
  z-index: 1;
}
nav.fill ul li a:hover:after {
  z-index: -10;
  animation: fill 1s forwards;
  -webkit-animation: fill 1s forwards;
  -moz-animation: fill 1s forwards;
  opacity: 1;
}

/* 
nav.shift ul li a {
  position:relative;
  z-index: 1;
}
nav.shift ul li a:hover {
  color: #91640F;
}
nav.shift ul li a:after {
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  margin: auto;
  width: 100%;
  height: 1px;
  content: '.';
  color: transparent;
  background: #F1C40F;
  visibility: none;
  opacity: 0;
  z-index: -1;
}
nav.shift ul li a:hover:after {
  opacity: 1;
  visibility: visible;
  height: 100%;
} */



/* @media (min-width: 320px) and (max-width: 768px) {

.logo_style
{ 
 max-height: 60px;
 max-width: 60px;
 margin-left: 0px;
} */






</style>