<script>
export default {
    name: "SiteBanner",
    data() {
    return {
      banner: [
        {
          text: 'Digital Comics',
          src: 'buy-comics-digital-comics.png'
        },
        {
          text: 'Merchandise',
          src: 'buy-comics-merchandise.png'
        },
        {
          text: 'Shop location',
          src: 'buy-comics-shop-locator.png'
        },
        {
          text: 'Subscription',
          src: 'buy-comics-subscriptions.png'
        },
        {
          text: 'DC Visa',
          src: 'buy-dc-power-visa.svg'
        },
      ]
    };
  },
  methods:{
    getImageUrl(name){
      return new URL(`../assets/img/${name}`, import.meta.url).href
    }
  }
}
</script>

<template>
    <main id="app_main">
    <div class="main_bottom">
      <div class="container">
        <div class="row justify-content-evenly">
          <div class="col-2 d-flex align-items-center" v-for='item in banner'>
            <img :src="getImageUrl(item.src)" alt=""/>
            <div class="ms-1">{{item.text}}</div>
          </div>
          <!-- <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/buy-comics-merchandise.png" alt="" />
            <div class="ms-1">Merchandise</div>
          </div> -->
          <!-- <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
            <div class="ms-1">Shop location</div>
          </div> -->
          <!-- <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
            <div class="ms-1">Subscription</div>
          </div> -->
          <!-- <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
            <div class="ms-1">DC Visa</div>
          </div> -->
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>

</style>