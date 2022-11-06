<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MercuryChat />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import { MercuryChat } from '@mercury-chat/vue-chat-previous';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MercuryChat
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
