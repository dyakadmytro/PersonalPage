<script setup>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import SectionHome from "@/components/sections/SectionHome.vue";
import SectionAbout from "@/components/sections/SectionAbout.vue";
import SectionServices from "@/components/sections/SectionServices.vue";
import SectionResume from "@/components/sections/SectionResume.vue";
import SectionPortfolio from "@/components/sections/SectionPortfolio.vue";
import SectionFaq from "@/components/sections/SectionFaq.vue";
import SectionTestimonial from "@/components/sections/SectionTestimonial.vue";
import SectionContact from "@/components/sections/SectionContact.vue";
import SectionBanner from "@/components/sections/SectionBanner.vue";
</script>
<!--https://picsum.photos/200/300-->
<template>
  <div id="main-wrapper">
  <Header/>
  <div id="content" role="main">
    <SectionHome/>
    <SectionAbout/>
    <SectionServices/>
    <SectionResume/>
    <SectionPortfolio/>
    <SectionBanner/>
    <SectionFaq/>
    <SectionTestimonial/>
    <SectionContact/>
  </div>
  <Footer/>
</div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
