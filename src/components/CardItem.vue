<script>

export default {
  name: "CardItem",
  props: {
    title: String,
    src: String
  }
};
</script>

<template>
  <div class="col">
    <div>
        <img :src="thumb" :alt="type">
        <h3> {{ series }} </h3>
    </div>
  </div>
</template>

<style lang="scss" scoped>
</style>
