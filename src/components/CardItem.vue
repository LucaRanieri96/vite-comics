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
        <img :src="src" alt="type">
        <p class="mt-2"> {{ title }} </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
    img{
        width: 100%;
        aspect-ratio: 1 / 1;
    }
    p{
        color: grey;
        &:hover{
            color: white;
        }
    }
    
</style>
