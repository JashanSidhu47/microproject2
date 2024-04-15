<template>
  <div id="app">
    <HelloWorld title="Sidhu Moosewala - Punjabi Singer"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Arial', sans-serif;
  color: #444;
  background-color: #f5f5f5;
  padding: 20px;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
