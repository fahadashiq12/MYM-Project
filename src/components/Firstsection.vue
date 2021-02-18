<template>

<div :style="{'background-image':'url(assets/Banner.jpg)'}" class="container-fluid image">
<div class="container">
<div class="row">
    <div class="style div_style">
    <div class="section col-xxl-6 col-xl-6 col-lg-6 col-md-12 col-sm-12">
    <h1> Simple & <span class="text_style"> Easy <br> to Use </span> </h1>
    <p class="p_style mt-4">  Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum is simply dummy text of the printing and typesetting industry.  Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
    <button type="submit" class="btn_style text-white mt-4" aria-label="Submit Button"> Get Started <span class="icon_style"> <i class="fa fa-angle-right"></i> </span></button>
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

    height: 100vh ;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;  
   

  }
  
  .btn_style
  {
    background-color: #1F4F46;
    border-radius: 5px;
    box-shadow: 20px 20px 50px #1F4F46;
    padding: 5px;
    display: inline-block;
    padding-left: 20px;
  }

  .div_style
  {
    
    text-align: left;
    margin-top: 200px;
    padding-left: 250px;
  }


.icon_style
{
   padding-left: 20px;
}

.style
{
    width: 1000px;
}


</style>