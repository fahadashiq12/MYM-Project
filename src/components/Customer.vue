<template>

<div class="customer_bg">
<div class="container">

  <div class="row">
        <div class="customer_style">
        <h1> Choose your Meal with Us </h1>
    </div>
    </div>

<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/assets/Canvas1 (3).png" class="" alt="...">
    </div>
    <div class="carousel-item">
       <img src="/assets/Canvas1 (1).png" class="" alt="...">
    </div>
    <div class="carousel-item">
       <img src="/assets/Canvas1 (2).png" class="" alt="...">
    </div>
  </div>
  <a class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls"  data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </a>
  <a class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls"  data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </a>
</div>









<!-- <div class="row">
 
  <div class="col-xxl-6 col-xl-6 col-lg-6 col-md-12 col-sm-12">
    
         <div class="customer_style div_style">
          <h1>
            Interact with <span class="txt_style"> Customers </span> <br> on Single Platform
          </h1>
          <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum is simply dummy text of the printing and typesetting industry.  Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p> 
          <button type="submit" class="btn_style mt-4" aria-label="Submit Button"> Get Started <span class="icon_style"> <i class="fa fa-angle-right"></i> </span></button>
      </div>
      </div>
        
   


  <div class="col-xxl-6 col-xl-6 col-lg-16 col-md-12 col-sm-12">
     
     <img src="/assets/Support2.png">
 
    
  </div>
   </div> -->

</div>
</div> 
</template>

<script>
export default {
  name: "Customer"
};


</script>

<style scoped>



.customer_style
{
  margin-top: 30px;
}


.customer_bg
{
  background-color: #E6FFFC;
  padding-bottom: 50px;
}

/* .customer_style
{
  width: 500px;
  text-align: left;
} */

.carousel-control-prev-icon{
    filter: brightness(0.5);
    border-radius: 100%;
    padding: 13px;
    
}

.carousel-control-next-icon{
  filter: brightness(0.5);
  border-radius: 100%;
  padding: 13px;
}

 .div_style
  {
    margin-left: auto;
    margin-right: auto;
    text-align: left;
    padding-bottom: 50px;
    /* margin-left: 300px; */
    margin-top: 10px;
  }

 
  .btn_style
  {
    background-color: transparent;
    border-radius: 5px;
    padding: 5px;
    display: inline-block;
    padding-left: 20px;
  }

/* button:hover
{
  background-color: #1F4F46;
  box-shadow: 4px 2px 3px rgb(161, 161, 161);
  color: white;
} */

.txt_style
{
font-weight: bolder ;  
}


.icon_style
{
   padding-left: 20px;
}

@media (min-width:1200px) and (max-width: 2000px) 
{


}

@media (min-width:992px) and (max-width: 1199px) 
{


}

@media (min-width:768px) and (max-width: 991px) 
{

.div_style[data-v-5d7a810e] {
    margin-left: auto;
    margin-right: auto;
    margin-top: 120px;
    text-align: left;
}


.carousel-item img, svg {
    vertical-align: middle;
    max-width: 100%;
}

}

@media (min-width:576px) and (max-width: 767px) 
{

.carousel-item img, svg {
    vertical-align: middle;
    max-width: 100%;
}

}


@media (min-width:320px) and (max-width: 575px) 
{



.carousel-item img, svg {
    vertical-align: middle;
    max-width: 100%;
}


  
}


</style>