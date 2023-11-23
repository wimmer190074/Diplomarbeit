<template>
  <div class="uk-background-muted">
    <NavBar></NavBar>
    <div class="uk-height-max-large uk-height-medium uk-flex uk-flex-center uk-flex-middle uk-background-cover uk-background-cover uk-background-center-center uk-light pad"
      data-src="/src/assets/images/hero-bg.jpg" uk-img>
    </div>
   
    <Imprint></Imprint>
  </div>
</template>
<script lang="ts">
import NavBar from "@/components/E2milyNavBar.vue";
import Imprint from "@/components/E2milyImprint.vue";
import AuszeichnungsRow from "@/components/AuszeichnungsRow.vue";
import AbteilungsCard from "@/components/AbteilungsCard.vue";
import ScrollTop from "@/components/ScrollTop.vue";
import HeroSection from "@/components/HeroSection.vue"

export default {
  name: 'E2milyView',
  components: {
    NavBar,
    Imprint,
    AuszeichnungsRow,
    AbteilungsCard,
    ScrollTop,
    HeroSection,
  },
};
</script>

<style>
/* Styles for this component */
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding-left: 100px;
  padding-right: 100px;
  padding-bottom: 50px;
  padding-top: 50px;
  position: relative;
}
.pad {
  padding-bottom: 50px;
}
@media (max-width: 640px) {
  .grid-container {
    grid-template-columns: 1fr;
    padding-left: 35px;
    padding-right: 35px;
    padding-bottom: 15px;
    padding-top: 15px;
  }
}
</style>
