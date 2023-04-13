<script>
export default {
  data() {
    return {
      message: "Hello world with Vite!",
    };
  },
};
</script>

<template>
  <header id="app_header">
    <div class="container">
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
      <div class="container_main">
        <div class="main_content">
          <h3>Content goes here</h3>
        </div>
      </div>
    </div>
    <div class="main_bottom">
      <div class="container_main">
        <div class="blue_banner">
          <div>
            <img src="./assets/img/buy-comics-digital-comics.png" alt="" />
            <span>Digital Comics</span>
          </div>
          <div>
            <img src="./assets/img/buy-comics-merchandise.png" alt="" />
            <span>Merchandise</span>
          </div>
          <div>
            <img src="./assets/img/buy-comics-shop-locator.png" alt="" />
            <span>Shop location</span>
          </div>
          <div>
            <img src="./assets/img/buy-comics-subscriptions.png" alt="" />
            <span>Subscription</span>
          </div>
          <div>
            <img src="./assets/img/buy-dc-power-visa.svg" alt="" />
            <span>DC Visa</span>
          </div>
        </div>
      </div>
    </div>
  </main>

  <footer id="app_footer">
    <div class="footer_top">
      <div>
        <div id="dc_comics">
          <h5>DC COMICS</h5>
          <ul>
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
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
      </div>
      <div id="dc">
        <h5>DC</h5>
        <ul>
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
        <ul>
          <li>Terms Of Use</li>
          <li>Privacy policy(new)</li>
          <li>Ad choices</li>
          <li>Advertising</li>
          <li>jobs</li>
        </ul>
      </div>
    </div>
    <div class="footer_bottom"></div>
  </footer>
</template>

<style scoped></style>
