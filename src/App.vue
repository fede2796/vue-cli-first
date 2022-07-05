<template>
  <div id="app">
    <Title></Title>
    <ImageVue/>
  </div>
</template>

<script>
import ImageVue from './components/hero.vue'
import Title from './components/title.vue'
export default {
  name: 'App',
  components: {
    ImageVue,
    Title
}
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
    border: 1px black solid;
    height: 400px;
  }
</style>
