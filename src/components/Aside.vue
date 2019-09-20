<template lang="pug">
  el-aside
    .menu
      el-button
        font-awesome-icon(icon="bars" size="2x")
    .logo
      h2 POMODORO
</template>

<style lang="scss" scoped>
  .el-aside {
    height: 80vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .el-button {
    border: none;
    background-color: $main;
    border-radius: 0;
  }
  h2 {
    writing-mode: vertical-rl;
    margin-left: auto;
    margin-right: auto;
  }

</style>
