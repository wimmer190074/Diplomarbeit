<template>
    <div>
      <NavBarEmily></NavBarEmily>
      <div class="uk-height-viewport uk-flex uk-flex-center uk-flex-middle">
        <img
          class="uk-width-1-1 uk-height-1-1"
          src="/src/assets/images/emily_hero.jpg"
          alt="Fullscreen Image"
        />
        <div class="text-overlay">
          <h1>E²MILY</h1>
        </div>
      </div>
      <div>
        <div>
          <div class="text">
            <h1>Kurzes Intro oder so</h1>
          </div>
          <div class="textparagraph">
            <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.</p>
          </div>
        </div>
        <div class="uk-background-muted">
          <div class="text">
            <h1>Team</h1>
          </div>
          <div class="textparagraph">
            <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.</p>
          </div>
        </div>
        <div>
          <div class="text">
            <h1>Sponsoren</h1>
          </div>
          <div class="textparagraph">
            <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.</p>
          </div>
        </div>
      </div>
      <ImprintEmily></ImprintEmily>
    </div>
</template>
  
<script lang="ts">
import NavBarEmily from '@/components/NavBarEmily.vue';
import ImprintEmily from '@/components/ImprintEmily.vue';
  
export default {
   name: 'EmilyView',
   components: {
    NavBarEmily,
    ImprintEmily
  },
};
</script>
  
<style>
.text-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

.text {
  padding-left: 100px;
  padding-right: 100px;
  padding-top: 50px;
}

.textparagraph {
  padding-left: 100px;
  padding-right: 100px;
  padding-bottom: 50px;
  padding-top: 25px;
}

</style>
  