<template>
  <Hero />
  <About />
</template>

<script>
// @ is an alias to /src
import Hero from "@/components/Hero.vue";
import About from "@/components/About.vue";

export default {
  name: "Home",
  components: {
    Hero,
    About,
  },
};
</script>
