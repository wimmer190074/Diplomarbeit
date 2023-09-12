<template>
  <div class="uk-position-top uk-">
    <nav class="uk-navbar-container uk-navbar-transparent">
      <div class="uk-container">
          <div uk-navbar>
              <div class="uk-navbar-center">

                  <div class="uk-navbar-center-left">
                      <ul class="uk-navbar-nav">
                          <li><a href="#">News</a></li>
                          <li>
                              <a href="#">Sponsoren</a>
                              <div class="uk-navbar-dropdown">
                                  <ul class="uk-nav uk-navbar-dropdown-nav">
                                      <li><a href="#">Sponsor werden</a></li>
                                      <li><a href="/e2mily/sponsoren">Sponsorenliste</a></li>
                                  </ul>
                              </div>
                          </li>
                      </ul>
                  </div>
                    <router-link class="uk-navbar-item uk-logo" to="/e2mily">
                      <img
                        src="/src/assets/images/emily_logo_small.png"
                        width="200"
                        height=""
                        alt="Emily Logo"
                      />
                    </router-link>
                  <div class="uk-navbar-center-right">
                    <ul class="uk-navbar-nav">
                          <li><a href="#">Kontakt</a></li>
                    </ul> 
                    <ul class="uk-navbar-nav uk-iconnav">
                        <!-- Social bar -->
                        <li><a href="https://youtube.com/playlist?list=PLeN1AHKZwig9eg0dtm7Hd86eQkPKRjqBd&si=X9hRs0BrT1MqDB4-" uk-icon="icon: youtube"></a></li>
                        <li><a href="https://www.facebook.com/HTLWeiz/" uk-icon="icon: facebook"></a></li>
                    </ul>              
                  </div>

              </div>

          </div>
      </div>
    </nav>
  </div>
</template>


<script lang="ts">
/* import ... from ...; */

export default {
  name: "NavbarEmily",
  components: {
    /*,*/
  },
};
</script>

<style>
/* Styles for this component */
.img-logo {
  max-height: 5%;
}

</style>

<!--
<div class="uk-position-relative">
  <div class="uk-position-top">
    <div uk-sticky="sel-target: .uk-navbar-container; cls-active: uk-navbar-sticky;">




      <nav class="uk-navbar-container uk-navbar-transparent" uk-navbar>
        <div class="uk-container">
          <div uk-navbar>
            <div class="uk-navbar-center">
              <div class="uk-navbar-center-left">
                <ul class="uk-navbar-nav">
                    <li class="uk-active"><a href="#">Active</a></li>
                    <li>
                        <a href="#">Parent</a>
                        <div class="uk-navbar-dropdown">
                            <ul class="uk-nav uk-navbar-dropdown-nav">
                                <li class="uk-active"><a href="#">Active</a></li>
                                <li><a href="#">Item</a></li>
                                <li><a href="#">Item</a></li>
                            </ul>
                        </div>
                    </li>
                </ul>
              </div>
            </div>
            <a class="uk-navbar-item uk-logo" href="/src/assets/images/Logo_HTL_2013_Small.png">Logo</a>
            <div class="uk-navbar-center-right">
                <ul class="uk-navbar-nav">
                    <li><a href="#">Item</a></li>
                    <li><a href="#">Item</a></li>
                </ul>
            </div>
          </div>
        </div>
      </nav>



      
    </div>
  </div>
</div>
</div>
-->