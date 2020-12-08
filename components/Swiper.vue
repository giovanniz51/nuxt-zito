<template>
<client-only>
  <flickity ref="flickity" :options="flickityOptions">
  <div class="carousel-cell img1"></div>
  <div class="carousel-cell img2"></div>
</flickity>
</client-only>
</template>

<script>
  export default {
    name: 'Swiper',
  data() {
    return {
      flickityOptions: {
        freeScroll: true,
        wrapAround: true,
        prevNextButtons: true,
        fade: true
      }
    }
  },
  }
</script>

<style lang="scss" scoped>
.carousel-cell{
  width: 100%;
  min-height: 40rem;

  &.img1 {
    background: url("/pexels-monoar-rahman-114907.jpg");
    background-size: cover;
    background-position: center;
  }
  &.img2 {
    background: url("/pexels-monoar-rahman-109371.jpg");
    background-size: cover;
    background-position: center;
  }
}


</style>
