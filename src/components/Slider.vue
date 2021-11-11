<template>
  <div class="backgroundRed">
    <h1>Hello</h1>
    <Carousel
      :per-page="1"
      :navigate-to="someLocalProperty"
      :mouse-drag="false"
    >
      <Slide> Slide 1 Content </Slide>
      <Slide> Slide 2 Content </Slide>
    </Carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from "vue-carousel";

export default {
  name: "Slider",
  components: {
    Carousel,
    Slide,
  },
};
</script>
