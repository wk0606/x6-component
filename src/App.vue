<template>
  <div id="app">
    <el-input v-model="name" placeholder="请输入内容"></el-input>
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return {
      name: ''
    }
  }
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
