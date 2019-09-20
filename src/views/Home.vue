<template lang="pug">
  el-main
    el-row
      el-col(:span="12")
        Pomodoro
</template>

<script>
import Pomodoro from '@/components/Pomodoro.vue'

export default {
  name: 'home',
  components: {
    Pomodoro
  }
}
</script>

<style lang="scss" scoped>
 .el-main {
   padding-top: 0px;
 }
</style>
