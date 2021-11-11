<template>
  <Hero />
  <About />
  <Projects />
</template>

<script>
// @ is an alias to /src
import Hero from "@/components/Hero.vue";
import About from "@/components/About.vue";
import Projects from "@/components/Projects.vue";

export default {
  name: "Home",
  components: {
    Hero,
    About,
    Projects,
  },
};
</script>
