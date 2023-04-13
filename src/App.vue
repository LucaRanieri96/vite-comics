<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorldDue from './components/HelloWorldDue.vue'
export default {
  components: {
    HelloWorld,
    HelloWorldDue
  },
  data() {
    return {
      message: "Hello world with Vite!",
    };
  },
};
</script>

<template>
  <!-- <HelloWorld></HelloWorld>
  <HelloWorldDue></HelloWorldDue> -->
  <header id="app_header" class="py-2">
    <div class="container d-flex align-items-center justify-content-between">
      <div class="logo">
        <img src="./assets/img/dc-logo.png" alt="" />
      </div>
      <div class="nav">
        <div><a href="#">CHARACTERS</a></div>
        <div><a href="#">COMICS</a></div>
        <div><a href="#">MOVIES</a></div>
        <div><a href="#">TV</a></div>
        <div><a href="#">GAMES</a></div>
        <div><a href="#">COLLECTIBLES</a></div>
        <div><a href="#">VIDEOS</a></div>
        <div><a href="#">FANS</a></div>
        <div><a href="#">NEWS</a></div>
        <div><a href="#">SHOP</a></div>
      </div>
    </div>
  </header>

  <main id="app_main">
    <div class="main_top">
      <div class="container">
        <div class="py-5">Content goes here</div>
      </div>
    </div>
    <div class="main_bottom">
      <div class="container">
        <div class="row justify-content-evenly">
          <div class="col-2 d-flex align-items-center">
            <img src="./assets/img/buy-comics-digital-comics.png" alt="" />
            <div class="ms-1">Digital Comics</div>
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="./assets/img/buy-comics-merchandise.png" alt="" />
            <div class="ms-1">Merchandise</div>
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="./assets/img/buy-comics-shop-locator.png" alt="" />
            <div class="ms-1">Shop location</div>
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="./assets/img/buy-comics-subscriptions.png" alt="" />
            <div class="ms-1">Subscription</div>
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="./assets/img/buy-dc-power-visa.svg" alt="" />
            <div class="ms-1">DC Visa</div>
          </div>
        </div>
      </div>
    </div>
  </main>

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
