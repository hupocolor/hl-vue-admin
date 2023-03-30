<template>
  <div class="dashboard-container">
    <div class="dashboard-text">
      欢迎使用狐狸博客管理系统
    </div>
    <div>
      <a href="https://github.com/hupocolor">GitHub:https://github.com/hupocolor</a>
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
