<template>
  <div id="app">
    <MainHeader/>
    <MyJumbotron/>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MyJumbotron from './components/MyJumbotron.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    MyJumbotron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
