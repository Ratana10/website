<template>
  <!-- <div style="">
    <h1>House with Beauty backyard</h1>
    <div class="row row-cols-4">
      <div class="box">
        <img src="/img.jpg" alt="" />
        <p class="text">Taddy Town</p>
        <p class="small-text">Gunung Batu, Indonesia</p>
      </div>
      <div class="box">
        <img src="/img.jpg" alt="" />
        <p class="text">Taddy Town</p>
        <p class="small-text">Gunung Batu, Indonesia</p>
      </div>
    </div>
  </div> -->
  <div style="">
    <h1>House with Beauty backyard</h1>
    <div class="d-flex">
      <div class="box me-auto ">
        <img src="/img.jpg" alt="" />
        <p class="text">Taddy Town</p>
        <p class="small-text">Gunung Batu, Indonesia</p>
      </div>
      <div class="box me-auto">
        <img src="/img.jpg" alt="" />
        <p class="text">Taddy Town</p>
        <p class="small-text">Gunung Batu, Indonesia</p>
      </div>
      <div class="box me-auto">
        <img src="/img.jpg" alt="" />
        <p class="text">Taddy Town</p>
        <p class="small-text">Gunung Batu, Indonesia</p>
      </div>
      <div class="box me-auto">
        <img src="/img.jpg" alt="" />
        <p class="text">Taddy Town</p>
        <p class="small-text">Gunung Batu, Indonesia</p>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style scoped>
h1 {
  font-size: 24px;
  font-weight: 500px;
  color: #152c5b;
  margin-bottom: 20px;
}
.box {
  width: 263px;
  height: 249px;
}
img {
  width: 263px;
  height: 180px;
  border-radius: 15px;
}
.text {
  color: #152c5b;
  font: 20px;
  margin-top: 16px;
  margin: 16px 0 1px 0;
}
.small-text {
  color: #b0b0b0;
  font-size: 15px;
}
</style>
