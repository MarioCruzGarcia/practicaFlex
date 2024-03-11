<script setup>
import Videos from "./components/Videos.vue";
import Audios from "./components/Audios.vue";
import Imagenes from "./components/Imagenes.vue";
</script>

<template>
  <div id="app">
    <header>
      <h1>Multimedia</h1>
    </header>
    <main>
      <Videos />
      <Audios />
      <Imagenes />
    </main>
    <footer>
      <p>© 2024 Multimedia Mario Cruz</p>
    </footer>
  </div>
</template>

<style scoped>
#app {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

header {
  background-color: #000000;
  color: #fff;
  padding: 20px;
}

h1 {
  margin: 0;
  text-align: center;
}

main {
  padding: 20px;
}

footer {
  background-color: #000000;
  color: #fff;
  padding: 10px 20px;
  text-align: center;
}
</style>
