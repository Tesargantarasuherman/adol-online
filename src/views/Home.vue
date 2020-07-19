<template>
  <div class="home">
    <Header />
    <Slider />
    <Banner />
    <Insta />
    <Partner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import Slider from '@/components/Slider.vue';
import Banner from '@/components/Banner.vue';
import Insta from '@/components/Insta.vue';
import Partner from '@/components/Partner.vue';
import Footer from '@/components/Footer.vue';
export default {
  name: "Home",
  components: {
    Header,
    Slider,
    Banner,
    Insta,
    Partner,
    Footer
  }
};
</script>
