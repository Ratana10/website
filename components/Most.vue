<template>
  <div style="">
    <h1 class="">Most Picked</h1>
    <div class="row">
      <div class="col-4">
        <img src="/img.jpg" alt="" class="box-img-big rounded-4" />
      </div>
      <div class="col-8">
        <div class="row row-cols-2">
          <div class="col mb-4">
            <img src="/img.jpg" alt="" class="box-img rounded-4" />
          </div>
          <div class="col mb-4">
            <img src="/img.jpg" alt="" class="box-img rounded-4" />
          </div>
          <div class="col mb-4">
            <img src="/img.jpg" alt="" class="box-img rounded-4" />
          </div>
          <div class="col mb-4">
            <img src="/img.jpg" alt="" class="box-img rounded-4" />
          </div>
        </div>
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

.box-img-big {
  width: 361px;
  height: 460px; /* Maintain aspect ratio */
  object-fit: cover;
}

.box-img {
  width: 361px; /* Adjust the width to fill the column */
  height: 215px; /* Maintain aspect ratio */
  object-fit: cover;
}
</style>
