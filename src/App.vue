<template>
  <div id="app">
    <x-input size="mini" type="card" v-model="name" :editable="true"/>
  </div>
</template>

<script>
import XInput from './components/Input/index'
export default {
  name: 'App',
  data(){
    return {
      name: 0
    }
  },
  components: { XInput }
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
