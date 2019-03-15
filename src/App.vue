<template>
  <div id="app">
    <HomeComponent></HomeComponent>
  </div>
</template>

<script>
import HomeComponent from './layouts/HomeComponent.vue'

export default {
  name: 'app',
  components: {
    HomeComponent
  },
  data: function(){
    return {
      demo: 'Demo text',
    }
  },
  methods: {
    demo1(){
      console.log(11111111111);
    },
  },
  computed: {
    reversedMessage: function(){
      return this.message.split('').reverse().join(' ');
    }
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
