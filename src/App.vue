<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://tecbasucre.com/" target="_blank">
      <img src="./assets/IMGtecba.png" class="logo" alt="Vite logo" />
    </a>
    <a href="https://web.tecba.tech/saeta/" target="_blank">
      <img src="./assets/images.jpeg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <router-view />
</template>

<style scoped>
.logo {
  height: 11em;
  padding: 5.5em;
  will-change: filter;
  transition: filter 400ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #f57905e3);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #c309db);
}
</style>
