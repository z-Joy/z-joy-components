<template>
  <div id="app">
    <h2>头像组件</h2>
    <avatar></avatar>
  </div>
</template>

<script>
import avatar from '@/components/avatar/index'; // 引入
export default {
  name: 'app',
  data () {
    return {
    }
  },
  components:{ //注册插件
    avatar
  },
  methods:{
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