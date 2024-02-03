<template>
  <p>Hello {{ name }}</p>
  <p v-text="channel"></p>
  <p>Test</p>
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
      name: "Rebecca 2",
      channel: "Illongga Frau"
    }
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
