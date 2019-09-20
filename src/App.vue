<template lang="pug">
  #app
    el-container
      router-view
      Aside
</template>

<script>
import Aside from '@/components/Aside.vue'
export default {
  name: 'app',
  components: {
    Aside
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif, 微軟正黑體;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
