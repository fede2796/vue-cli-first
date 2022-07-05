<template>
  <div>
    <h1>Ciao a tutti</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  h1 {
   color: #2c3e50;
   font-size: 60px;
  }
</style>