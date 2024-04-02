<script lang="ts" setup>
const navbar = [
  { name: "Home", href: "/" },
  { name: "Browse by", href: "/" },
  { name: "Stories", href: "/" },
  { name: "Agents", href: "/" },
];
</script>
<template>
  <nav class="navbar navbar-expand-lg mt-1 border-bottom" style="height: 80px">
    <div class="d-flex flex-grow-1">
      <a class="navbar-brand d-none d-lg-inline-block fs-4" href="#">
        Staycation.
      </a>
    </div>
    <div class="collapse navbar-collapse flex-grow-1 text-right" id="myNavbar">
      <ul class="navbar-nav ms-auto flex-nowrap">
        <li class="nav-item" v-for="item in navbar">
          <a href="#" class="nav-link m-2 menu-item nav-active fs-6">{{
            item.name
          }}</a>
        </li>
      </ul>
    </div>
  </nav>
</template>
