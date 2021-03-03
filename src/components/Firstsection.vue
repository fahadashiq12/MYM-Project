<template>

<div :style="{'background-image':'url(assets/Banner.jpg)'}" class="container-fluid image" id="firstsection">
<div class="container">
    
    <div class="row">
    <div class="style div_style">
    <div class="col-xxl-6 col-xl-6 col-lg-12 col-md-12 col-sm-12">
    <h1> Simple & <span class="text_style"> Easy <br> to Use  </span>  </h1>
    <p class="p_style mt-4">  Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum is simply dummy text of the printing and typesetting industry.  Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
    <button type="submit" class="btn_style mt-4" aria-label="Submit Button"> Get Started <span class="icon_style"> <i class="fa fa-angle-right"></i> </span></button>
    </div>
    </div>
    </div>


</div>   
</div> 

</template>

<script>
export default
{
    name: "Firstsection"
};
</script>

<style scoped>

  .image 
  {
    height: 100vh;
    max-width: 100%; 
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
   }
 

  
  .btn_style
  {
    background-color: transparent;
    border-radius: 5px;
    padding: 5px;
    display: inline-block;
    padding-left: 20px;
  }

  .div_style
  {  
    text-align: left;
    margin-top: 280px;
    margin-left: 250px;
  }


.icon_style
{
   padding-left: 20px;
}

.style
{
    width: 1000px;
}

button:hover
{
  background-color: #1F4F46;
  box-shadow: 4px 2px 3px rgb(161, 161, 161);
  color: white;
}


.text_style
{

font-weight: bolder;

}

@media (min-width: 1504px) and (max-width: 2000px)
{
.div_style {
    text-align: left;
    margin-top: 250px !important;
    margin-left: 200px;
}

}

@media (min-width: 1200px) and (max-width: 1503px) 
{

.div_style {
    text-align: left;
    margin-top: 20+0px !important;
    padding-left: 200px !important; 
    margin-left: 0px;
}


}

@media (min-width: 992px) and (max-width: 1199px) 
{



.div_style
{
    text-align: left;
    margin-top: 180px;
    margin-left: 0px !important;
    width: 500px;
    padding-left: 100px;
}


}





@media (min-width: 768px) and (max-width: 991px) 
{

.div_style[data-v-6b2eb7e5] {
    text-align: left;
    margin-top: 200px;
    padding-left: 15px;
}

.div_style{
    text-align: left;
    margin-top: 280px;
    margin-left: 0px;
}


.style {
    width: 440px;
}

}


@media (min-width: 576px) and (max-width: 767px) 
{



  .div_style 
  {
    text-align: left;
    margin-top: 200px !important;
    margin-left: 0px !important;
}

}


@media (min-width: 320px) and (max-width: 575px) 
{



.div_style{
    text-align: left;
    margin-top: 60px;
    margin-left: 0px !important;
}



.style
{
    padding: 0px !important;
    border-radius: 8px;
}




}



</style>