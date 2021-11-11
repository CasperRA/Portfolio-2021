<template>
  <Slider />
  <div>
    <h2 class="sectionIntro">My <span class="highlight"> Projects</span></h2>
    <h1 class="sectionTitle">PROJECTS</h1>
  </div>
</template>

<script>
import Slider from "@/components/Slider.vue";
export default {
  name: "Projects",
  props: {
    msg: String,
  },
  components: {
    Slider,
  },
};
</script>
