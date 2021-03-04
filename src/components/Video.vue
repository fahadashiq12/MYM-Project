<template>
        <div :style="{'background-image':'url(assets/Videobg.png)'}" class="container-fluid image" id="video">
        <div class="row">
        <div class="video_style">
        <div class="col-xxl-12 col-xl-12 col-lg-12 col-md-12 col-sm-12">
        <h1>
        Check Our <span class="txt_style"> Videos </span> <br> Feature Below
        </h1>
        </div>

        <div class="col-xxl-12 col-xl-12 col-lg-12 col-md-12 col-sm-12" style="max-width: 100%">
        <div class="video_box">
        <div class="iframe_style">
        <!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/5fJDJ8HOFeo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
        <iframe width="560" height="315" class="responsive-iframe" src="https://www.youtube.com/embed/oGfOfPSXJvI" ></iframe>
        <div class="style">
        <!-- <a href="" class="palybtn"><i class="fa fa-play-circle"></i> </a> -->
        </div>
        </div>
        </div>
        </div>
        </div>
        </div>
        </div> 


     
       <div class="container-fluid">
       <video autoplay muted loop id="myVideo" style="max-width: 100%">
        <source src="/assets/OldVideo2.mp4" type="video/mp4">
       </video>
       </div>



       



           
</template>

<script>

export default 
{
   name: "Videos"
};

</script>


<style>

.video_style
{
  padding-top: 50px;
  padding-bottom: 50px;
}


.palybtn
{

color: #1F4F46;
max-width: 100%;


}



/* Then style the iframe to fit in the container div with full height and width */
.responsive-iframe {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 100%;
    /* height: 100%; */
    border-radius: 25px;
    height: 380px;
}

.video_box {
    border: 10px Solid #1F4F46;
    border-radius: 35px;
    height: 460px;
    /* width: 800px; */
    margin-left: 400px;
    margin-top: 100px;
    max-width: 100%;
    margin-bottom: 40px;
}
.video_box {
    border: 10px Solid #1F4F46;
    border-radius: 35px;
     height: 460px;
    width: 900px;
    margin-left: 400px;
    margin-top: 100px;
    max-width: 100%;
    margin-bottom: 40px;
}

.image
{
height: 100%;
background-repeat: no-repeat;
background-position: center;
background-size: cover; 
}

.iframe_style {
    /*  position: relative; */
    overflow: hidden;
    width: 100.2%;
    /* padding-top: 56.    25%; */
    margin-left: -1px;
}

.iframe_style
{
    position: relative;
    overflow: hidden;
    width: 100.2%;
    padding-top: 56.25%;
    margin-left: -1px;
}

.txt_style
{   
font-weight: bolder;
}


.video_box:hover
{
 box-shadow: 10px 2px 50px #969696;
}


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

    
.responsive-iframe {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 100%;
    border-radius: 25px;
    height: 175px;
}


.iframe_style
{
    position: relative;
    overflow: hidden;
    width: 100.2%;
    padding-top: 56.25%;
    margin-left: -1px;
    height: 175px;
}

.responsive-iframe {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 100%;
    border-radius: 25px;
    height: 178px;
}

.video_box 
{
border: 10px Solid #1F4F46;
border-radius: 34px;
height: 197px !important;
width: 1000px;
margin: 36px auto;
}


}

@media (min-width:320px) and (max-width: 575px) 
{


.responsive-iframe {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 100%;
    border-radius: 25px;
    height: 175px;
}


.iframe_style
{
    position: relative;
    overflow: hidden;
    width: 100.2%;
    padding-top: 56.25%;
    margin-left: -1px;
    height: 175px;
}

.responsive-iframe {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 100%;
    border-radius: 25px;
    height: 178px;
}

.video_box 
{
border: 10px Solid #1F4F46;
border-radius: 34px;
height: 197px !important;
width: 1000px;
margin: 36px auto;
}

.image
{
/* background-image: url(assets/Videobg.png); */
height: 400px !important;
}



.card
{
    border: 0;
    box-shadow: 0px 0px 15px -8px rgb(182 182 182);
    margin-bottom: 15px !important;
}


.card_style
{
    padding: 20px !important;
    padding-bottom: 15px !important;
    margin: 0px !important;
}
  
}

</style>