<template>
  <div id="app">
    <MainHeader/>
    <MyHero/>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    MyHero
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
