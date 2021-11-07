<template>
  <!-- <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div> -->
  <router-view />
</template>

<script>
import "bootstrap/dist/css/bootstrap.min.css";

export default {};
</script>

<style lang="scss">
@import "@/assets/_shared.scss";

body {
  background-color: $primary;
  height: 200vh;
  color: $white;
  font-family: $font;
}
</style>
