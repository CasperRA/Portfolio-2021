<template>
  <section id="background-hero"></section>
  <Nav />
  <section id="intro">
    <img src="@/assets/selflogo.png" alt="" />
    <h1>
      CASPER REEDTZ <br />
      ANDERSEN
    </h1>
  </section>
</template>

<script>
import Nav from "@/components/Nav.vue";

export default {
  name: "Hero",
  props: {
    msg: String,
  },
  components: {
    Nav,
  },
};
</script>
