<script>
export default {
  name: "SiteHeader",
  data() {
    return {
      menu: [
        {
          text: "CHARACTERS",
          href: "#",
          currentPage: false,
        },
        {
          text: "COMICS",
          href: "#",
          currentPage: false,
        },
        {
          text: "MOVIES",
          href: "#",
          currentPage: false,
        },
        {
          text: "TV",
          href: "#",
          currentPage: false,
        },
        {
          text: "GAMES",
          href: "#",
          currentPage: false,
        },
        {
          text: "COLLECTIBLES",
          href: "#",
          currentPage: false,
        },
        {
          text: "VIDEOS",
          href: "#",
          currentPage: false,
        },
        {
          text: "FANS",
          href: "#",
          currentPage: false,
        },
        {
          text: "NEWS",
          href: "#",
          currentPage: false,
        },
        {
          text: "SHOP",
          href: "#",
          currentPage: false,
        },
      ],
    };
  },
};
</script>

<template>
  <header id="app_header" class="py-2">
    <div class="container d-flex align-items-center justify-content-between">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="" />
      </div>
      <div class="nav">
        <div v-for="item in menu">
          <a href="#">{{ item.text }}</a>
        </div>
        <!-- <div><a href="#">COMICS</a></div>
        <div><a href="#">MOVIES</a></div>
        <div><a href="#">TV</a></div>
        <div><a href="#">GAMES</a></div>
        <div><a href="#">COLLECTIBLES</a></div>
        <div><a href="#">VIDEOS</a></div>
        <div><a href="#">FANS</a></div>
        <div><a href="#">NEWS</a></div>
        <div><a href="#">SHOP</a></div> -->
      </div>
    </div>
  </header>
</template>

<style scoped lang="scss">
@use "../styles/partials/_variables.scss" as *;

header {
  background-color: white;
}
.nav {
  gap: 1rem;
  
  a {
    text-decoration: none;
    color: rgb(92, 92, 92);
    font-weight: 500;
    height: 100%;

    &:hover {
      cursor: pointer;
      color: $primary;
      border-bottom: 4px solid $primary;
    }
  }
}
</style>
