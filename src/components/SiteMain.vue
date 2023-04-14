<script>
import comics from "../data/comics.js"
import CardItem from "./CardItem.vue"

export default {
  name: "SiteMain",
  components : {
    CardItem,
  },
  data() {
    return {
      comics : comics,
    };
  },
  mounted() {
    console.log(comics);
  }
};
</script>

<template>
  <div id="banner"></div>

  <div class="main_top">
    <div class="container">
      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 row-cols-lg-6 py-5">

        <CardItem :src="comic.thumb" :title="comic.series" v-for="comic in comics" />

      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #banner{
    height: 600px;
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
  }
</style>
