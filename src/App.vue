<template>
  <div id="app">
    <Title msg="La mia prima app con Vue CLI!"/>
    <ImageVue />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import ImageVue from './components/Hero.vue'
export default {
  name: 'App',
  components: {
    Title,
    ImageVue
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
  }
</style>
