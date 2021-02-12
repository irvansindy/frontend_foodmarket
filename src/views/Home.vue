<template>
  <div class="home">
    <Header/>
    <Slider/>
    <About/>
    <StartQT/>
    <Menu/>
    <Gallery/>
    <CustomerReviews/>
    <ContactInfo/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Slider from '@/components/Slider.vue'
import About from '@/components/About.vue'
import StartQT from '@/components/StartQT.vue'
import Menu from '@/components/Menu.vue'
import Gallery from '@/components/Gallery.vue'
import CustomerReviews from '@/components/CustomerReviews.vue'
import ContactInfo from '@/components/ContactInfo.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Slider,
    About,
    StartQT,
    Menu,
    Gallery,
    CustomerReviews,
    ContactInfo,
    Footer
  }
}
</script>
