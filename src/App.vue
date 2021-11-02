<template>
  <!-- <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div> -->
  <router-view />
</template>

<script>
import 'bootstrap/dist/css/bootstrap.min.css'

export default {

}
</script>

<style lang="scss">
@import "@/assets/_shared.scss";
#background-hero {
  background-image: url("assets/hero.jpg");
  background-size: cover;
  background-color: red;
  width: 100%;
  height: 100vh;
  background-position-y: 40%;
  z-index: -1;
  opacity: 20%;
  position: absolute;
}

#intro {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: $orange;
  font-weight: bold;
  height: 100vh;
}

#intro img {
  width: 20%;
}

#intro h1 {
  margin-top: 2rem;
  font-weight: 800;
  font-size: 4.25em;
}

body {
  background-color: $primary;
  height: 200vh;
  color: $white;
  font-family: $font;
}
</style>
