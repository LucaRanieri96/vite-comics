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
    <div class="container_main">
      <div class="main_content">
        <h3>Content goes here</h3>
      </div>
    </div>
    <div class="blue_banner">
      <div>
        <img src="./assets/img/buy-comics-digital-comics.png" alt="">
        <span>Digital Comics</span>
      </div>
      <div>
        <img src="./assets/img/buy-comics-merchandise.png" alt="">
        <span>Merchandise</span>
      </div>
      <div>
        <img src="./assets/img/buy-comics-shop-locator.png" alt="">
        <span>Shop location</span>
      </div>
      <div>
        <img src="./assets/img/buy-comics-subscriptions.png" alt="">
        <span>Subscription</span>
      </div>
      <div>
        <img src="./assets/img/buy-dc-power-visa.svg" alt="">
        <span>DC Visa</span>
      </div>
    </div>
  </main>

  

  <footer id="app_footer"></footer>
</template>

<style scoped></style>
