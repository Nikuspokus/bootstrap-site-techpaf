<template>
  <div>
    <b-carousel
      id="carousel-fade"
      style="text-shadow: 0px 0px 2px #000"
      fade
      indicators
      img-width="100vh !important"
    >
      <b-carousel-slide
        class="carousel-item-2"
        caption="First slide"

      ></b-carousel-slide>
      <b-carousel-slide
        class="carousel-item-2"
        caption="Second Slide"
        img-src="https://picsum.photos/1024/480/?image=12"
      ></b-carousel-slide>
      <b-carousel-slide
        class="carousel-item-2"
        caption="Third Slide"
        img-src="https://picsum.photos/1024/480/?image=22"
      ></b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  name: "Carousel",
};
</script>

<style>
.carousel-item img {
  width: 100vh !important ;
}
.carousel-item-2 img {
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  width: 100%;
  height: 100%;
}
</style>
