<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteMain from './components/SiteMain.vue'

export default {
  components: {
    SiteHeader,
    SiteMain,
  },
  data() {
    return {
      
    };
  },
};
</script>

<template>

  <SiteHeader></SiteHeader>
  <SiteMain></SiteMain>

  <footer id="app_footer">
    <div class="footer_top p-3">
      <div class="container d-flex gap-5">
        <div class="m_right">
          <div id="dc_comics">
            <h5>DC COMICS</h5>
            <ul class="list-unstyled">
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>
          </div>
          <div id="shop">
            <h5>SHOP</h5>
            <ul class="list-unstyled">
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>
          </div>
        </div>
        <div id="dc" class="m_right">
          <h5>DC</h5>
          <ul class="list-unstyled">
            <li>Terms Of Use</li>
            <li>Privacy policy(new)</li>
            <li>Ad choices</li>
            <li>Advertising</li>
            <li>jobs</li>
            <li>Subscriptions</li>
            <li>News</li>
            <li>Subscriptions</li>
            <li>News</li>
            <li>Subscriptions</li>
            <li>News</li>
          </ul>
        </div>
        <div id="sites">
          <h5>SITES</h5>
          <ul class="list-unstyled">
            <li>Terms Of Use</li>
            <li>Privacy policy(new)</li>
            <li>Ad choices</li>
            <li>Advertising</li>
            <li>jobs</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer_bottom">
      <div class="container d-flex justify-content-between">
        <div id="sign_button">SIGN-UP NOW!</div>
        <div class="d-flex align-items-center gap-2">
          <div class="blue"><strong>FOLLOW US</strong></div>
          <img src="./assets/img/footer-facebook.png" alt="">
          <img src="./assets/img/footer-periscope.png" alt="">
          <img src="./assets/img/footer-pinterest.png" alt="">
          <img src="./assets/img/footer-twitter.png" alt="">
          <img src="./assets/img/footer-youtube.png" alt="">
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
@use "/node_modules/bootstrap/scss/bootstrap.scss";
@use "./styles/style.scss";

</style>
