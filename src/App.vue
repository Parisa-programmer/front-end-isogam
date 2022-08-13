<template>
  <v-app>
    <HeaderSite class="widthAll" />
    <ImagesComponent class="" />
    <AboutUs />
    <LogoFooter />
    <!-- <v-main>
      <router-view />
    </v-main>
     -->
  </v-app>
</template>

<script>
import HeaderSite from "@/components/HeaderSite.vue";
import ImagesComponent from "@/components/ImagesComponent.vue";
import AboutUs from "@/components/AboutUs.vue";
import LogoFooter from "@/components/LogoFooter.vue";
import './components/main.css'

export default {
  name: "App",
  components: {
    HeaderSite,
    ImagesComponent,
    AboutUs,
    LogoFooter,
  },
};
</script>


