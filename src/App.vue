<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyTitle />
    <HeroJumbotron/>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import HeroJumbotron from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    HeroJumbotron
}
}
</script>

<style>
#app {
  font-family: sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
