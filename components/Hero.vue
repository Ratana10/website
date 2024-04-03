<script lang="ts" setup>
const icons = [
  {
    name: "travelers",
    number: 80409,
    img: "lock.svg",
  },
  {
    name: "treasure",
    number: 80409,
    img: "camera.svg",
  },
  {
    name: "cities",
    number: 1402,
    img: "location.svg",
  },
];
</script>

<template>
  <div class="" style="height: 458px">
    <div class="row">
      <div class="col">
        <h1
          class="fw-bold"
          style="color: #152c5b; width: 422px; font-size: 42px"
        >
          Forget Busy Work, Start Next Vacation
        </h1>
        <p class="fs-6 mt-5" style="color: #b0b0b0; width: 333px">
          We provide what you need to enjoy your holiday with family. Time to
          make another memorable moments.
        </p>
        <button class="btn btn-primary mt-4 btn-shadow">Show Me Now</button>
        <!-- Icons -->
        <div class="d-flex" style="margin-top: 80px">
          <div style="height: 69px; margin-right: 40px" v-for="item in icons">
            <img
              :src="`/${item.img}`"
              alt=""
              style="width: 32px; height: 32px"
            />
            <p class="fs-6">
              <span class="fw-bold me-1">{{ item.number }}</span>
              <span style="color: #b0b0b0">{{ item.name }}</span>
            </p>
          </div>
        </div>
        <!-- End Icons -->
      </div>
      <div class="col">
        <img style="height: 450px; width: 559px" src="/hero.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.btn-shadow {
  box-shadow: 0px 8px 15px 0px #3252df4d;
}
</style>
