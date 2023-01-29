<script setup>
</script>

<template>
  <div class="heroes">
    <h1 id="heading"> My Favorite Heroes in Mobile Legends</h1>
  </div>
  <div class="images">
    <div class="img-wrapper"><img src="https://wallpapercave.com/wp/wp4956893.jpg" alt=""></div>
    <div class="img-wrapper"><img src="https://wallpapercave.com/wp/wp4285832.jpg" alt=""></div>
    <div class="img-wrapper"><img src="https://rare-gallery.com/thumbnail/1389264-Beatrix-Mobile-Legends-Video-Game.jpg" alt=""></div>
    <div class="img-wrapper"><img src="https://rare-gallery.com/thumbs/329470-Lapu-Lapu-Vulcan-Skin-Mobile-Legends-4K-iphone-wallpaper.jpg" alt=""></div>
    <div class="img-wrapper"><img src="https://rare-gallery.com/thumbnail/1384941-Lancelot-Odette-Mobile-Legends-MLBB-Video-Game.jpg" alt=""></div>
    
  </div>
</template>

<style>
  #heading {
    text-align: center;
    font-size: 3rem;
  }
  .heroes {
    margin: auto;
    background-color: rgba(44, 40, 40, 0.285);
    width: 46rem;
    border-radius: 10px;
  }
  img {
    width: 250px;
    transition: transform .5s ease;
    
  }
  .img {
    border-radius: 3px;
    border: 2px solid white;
  }
  .images {
    overflow: hidden;
    display: flex;
    justify-content: space-evenly;
  }

  .img-wrapper img:hover {
    transform: scale(1.1);
  }
</style>
