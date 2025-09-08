<script setup lang="ts"></script>

<template>
  <main></main>
  <aside></aside>
</template>

<style>
body {
  margin: 0;
  padding: 0;
}

* {
  box-sizing: border-box;
}

#app {
  display: flex;
}

main {
  width: 90%;
  height: 100vh;
  background-color: green;
}
aside {
  width: 10%;
  height: 100vh;
  background-color: red;
}
</style>
