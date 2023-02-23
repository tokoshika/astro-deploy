<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <h1>花はさく</h1>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/qa6pU8D9dRM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <!-- <h2>
      まっしろな　ゆきみちに　はるかぜかおる
    </h2>
    <h2>
      わたしは　なつかしい
    </h2> -->
    <h1>ありがとうの花</h1>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/Tc1B9Cck2wo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <a href="https://vitejs.dev" target="_blank">
      <br>
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <br>
  <img src="./assets/arigaou.jpg" alt="">
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
