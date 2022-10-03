<template>
  <div>
    <BannerPhrase/>
    <Header v-if="true"/>
    <Divider v-if="true"/>
    <ClothingCatalogPage v-if="false"/>
  </div>
  <Footer/>
</template>

<script>
import "@/assets/style/index.sass";
import Header from "@/components/Header";
import BannerPhrase from "@/components/Banners/BannerPhrase";
import Footer from "@/components/Footer";
import Divider from "@/components/Divider";
import ClothingCatalogPage from "@/components/ClothingCatalogPage";

export default {
  name: 'App',
  components: {
    ClothingCatalogPage,
    Divider,
    Footer,
    Header,
    BannerPhrase
  }
}
</script>

<style>

</style>
