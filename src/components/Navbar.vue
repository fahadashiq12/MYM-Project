<template>
<div>
<nav class="navstyle navbar navbar-expand-lg navbar-light">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-8 mb-lg-0">

        <li class="nav-item">   
          <a class="navbar-brand" href="#">
          <img class="logo_style" alt="Vue logo" src="/assets/Salada.png">
          </a>
        </li>
        
        <li class="nav-item">                       
           <a class="nav-link active" aria-current="page" href="#"> How it works</a>
        </li>

        <li class="nav-item">
        <a class="nav-link active" aria-current="page"  href="#"> About Us </a>
        </li>

        <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#"> Video </a>
        </li>
     
        <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#"> Pricing  </a>
        </li>
      
        <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#"> News  </a>
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
  padding-left: 10px;
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
 margin-left: 300px;
}



</style>