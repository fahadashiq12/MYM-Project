<template>

<div :style="{'background-image':'url(assets/Background.png)'}" class="container-fluid image">
<div class="row">
  <div class="video_style">
   <div class="col-xxl-12 col-xl-12 col-lg-12 col-md-6 col-sm-6">
       <h1>
           Check Our Videos <br> Feature Below
       </h1>
    </div>

    <div class="col-xxl-12 col-xl-12 col-lg-12 col-md-6 col-sm-6">
      <div class="video_box">

                <div class="iframe_style">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>
</div>

        </div>
     </div>
   </div>
  </div>
</div>
    
</template>

<script>

export default 
{
   name: "Videos"
};

</script>


<style scoped>

.video_style
{
  margin-top: 70px;
}

/* Then style the iframe to fit in the container div with full height and width */
.responsive-iframe 
{
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  /* height: 100%; */
   height: 270px; 
}

.video_box
{
border: 5px Solid #1F4F46;
border-radius: 5px;
height: 280px;
width: 700px;
margin-left: 400px;
margin-top: 100px;
}

.image
{
height: 100vh;
background-repeat: no-repeat;
background-position: center;
background-size: cover; 
}

.iframe_style
{
  position: relative;
  overflow: hidden;
  width: 100%;
  padding-top: 56.25%; /* 16:9 Aspect Ratio (divide 9 by 16 = 0.5625) */
 
}


</style>