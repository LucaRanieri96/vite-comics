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
      <div id="title">
        <h3>CURRENT SERIES</h3>
      </div>
      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 row-cols-lg-6 py-5">
        <CardItem :src="comic.thumb" :title="comic.series" v-for="comic in comics" />
      </div>
      <div class="d-flex justify-content-center pb-4">
        <button type="button" class="btn btn-primary">Load More</button>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../styles/partials/_variables.scss" as *;
  .main_top{
    position: relative;
  }
  #title{
    padding: 0.6rem;
    background-color: $primary;
    position: absolute;
    float: left;
    top: -26.39px;
    h3{
      margin: 0;
    }
  }

  #banner{
    height: 600px;
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
  }
</style>
