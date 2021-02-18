<template>
  <Navbar />
   <Firstsection />
  <!-- <img class="img_style" alt="First Background" src="./assets/Banner.jpg"> -->
  <Feature />
  <Video />
  <Tools />
  <Customer />
  <Support />
  <Pricing />
  <Testimonials />
  <Article />
  <Newsletter />
  <Footer />
  <!-- <img class="img2_style" alt="Tools Background" src="./assets/42.png"> -->
  <!-- <img alt="Vue logo" src="./assets/Salada.png">  -->
  <!-- <Home data="Salada First Component and we deal with all things together for all things we need for all things together we are able to "/> -->

</template>

<script>
import Firstsection from './components/Firstsection.vue';
import Navbar from './components/Navbar';
import Feature from './components/Feature';
import Video from './components/Video';
import Tools from './components/Tools';
import Customer from './components/Customer';
import Support from './components/Support';
import Pricing from './components/Pricing';
import Testimonials from './components/Testimonials';
import Article from './components/Article';
import Newsletter from './components/Newsletter';
import Footer from './components/Footer';
export default {
  name: 'App',
  components: {
    Navbar,
    Firstsection,
    Feature,
    Video,
    Tools,
    Customer,
    Support,
    Pricing,
    Testimonials,
    Article,
    Newsletter,
    Footer,
  }
}
</script>

<style>
#app 

{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}


.img_style
{
max-width: 100%;
max-height: 100%;
}

.img2_style
{
max-width: 100%;
max-height: 100%;
}


</style>
