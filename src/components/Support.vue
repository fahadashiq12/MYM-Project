<template>
<div :style="{'background-image':'url(assets/Videobg.png)'}" class="image">
<div  class="container" id="support">
<div class="support_bg">
     <div class="row">
        <div class="support_style">
        <h1> Customer Support </h1>
    </div>
    </div>

<div class="row contact-support">

            <div class="col-xl-6 col-lg-6 col-md-6 col-sm-12 contact-support-card text-center">
                <div class="">
                    <img src="/assets/Char1 (4).png" alt="" class="img">
                </div>
                <div class="contact-support-card__content mt-4 mb-4">
                    <h4> 24/7 Support </h4>
                    <p>
                        100+ articles to get the information you need when you need it.
                    </p>
                </div>
               <button type="submit" class="btn_style mt-4" aria-label="Submit Button"> Get Started <span class="icon_style"> <i class="fa fa-angle-right"></i> </span></button>
    
            </div>
          
            <div class="col-xl-6 col-lg-6 col-md-6 col-sm-12 contact-support-card text-center">
                <div class="contact-support-card__image">
                    <img src="/assets/Char1 (5).png" alt="" class="img">
                </div>
                <div class="contact-support-card__content mt-4 mb-4">
                    <h4>Helpline</h4>
                    <p>
                        100+ articles to get the information when you need it.
                    </p>
                </div>
                <button type="submit" class="btn_style mt-4" aria-label="Submit Button"> Get Started <span class="icon_style"> <i class="fa fa-angle-right"></i> </span></button>
    
            </div>
            
</div>
</div>
</div>
</div>

       
</template>

<script>
export default {
    name: "Support",
};
</script>


<style scoped>

.image
{
height: 100%;
background-repeat: no-repeat;
background-position: center;
background-size: cover; 
}

/* 
.vl {
  border-left: 6px solid green;
  height: 500px;
  position: absolute;
  left: 50%;
  margin-left: -3px;
  top: 0;
} */


.btn_style
{

background-color: #1F4F46!important;
color: white;

}

.btn_style
{

background-color: #1F4F46!important;
color: white;

}

.contact-support 
{
        /* border: 1px solid #ddd; */
        border-radius: 5px;
        margin: 0px 0;
}

.contact-support-card__image
{
        margin-top: 300px;
}


.img 
{
    max-width: 65% !important;
}

.contact-support-card 
{
        /* border-right: 1px solid #ddd; */
        /* padding: 40px; */
        /* margin-top: 25px; */
}

.contact-support-card:last-child
 {
        border: none;
    }

    .contact-support .contact-support-card__content h4 {
        font-size: 22px;
    }

    .button-card-green {
        border-radius: 0;
        background: #52A377;
        color: white;
        padding: 10px 25px;
        font-weight: 700;
    }

    .img
    {
        max-width: 100%;
    }
   

   .support_bg
   {
    
    margin-top: 15px;

   }

   .support_style{
       padding-top: 20px;
   }

    @media (max-width: 767px) {
        .contact-support-card {
            border: none;
            border-bottom: 1px solid #ddd;
        }
    }

    @media (max-width: 991px) and (min-width: 768px) {
        .contact-support-card {
            padding: 20px;
        }

        .button-card-green {
            padding: 10px;
        }
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

}


@media (min-width:320px) and (max-width: 575px) 
{



  
}

</style>