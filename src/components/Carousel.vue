<template>
    <div class="q-pa-md">
      <q-carousel
        animated
        v-model="slide"
        arrows
        navigation
        infinite
      >
        <q-carousel-slide :name="1" img-src="https://wallpapercave.com/wp/wp7141904.jpg" class="carousel-img" />
        <q-carousel-slide :name="2" img-src="https://w0.peakpx.com/wallpaper/172/111/HD-wallpaper-new-balance-golden-logo-artwork-brown-metal-background-creative-new-balance-logo-brands-new-balance.jpg" class="carousel-img" />
        <q-carousel-slide :name="3" img-src="https://fc02.deviantart.net/fs71/i/2010/244/a/7/reebok_wallpaper_by_discotea-d2xs93e.jpg" />
        <q-carousel-slide :name="4" img-src="https://c4.wallpaperflare.com/wallpaper/656/700/1024/patterns-brown-brown-patterns-louis-vuitton-hd-wallpaper-preview.jpg" class="carousel-img" />
      </q-carousel>
    </div>
  </template>
  
  <script>
  import { ref } from 'vue'
  
  export default {
    setup () {
      return {
        slide: ref(1)
      }
    }
  }
  </script>
  
  <style scoped>
  .carousel-img {
    height: 400px; /* Ubah sesuai kebutuhan */
    background-size: cover;
    background-position: center;
  }
  </style>