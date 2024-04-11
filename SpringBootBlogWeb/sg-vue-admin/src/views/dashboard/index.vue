<template>
  <div class="dashboard-container">
    <div class="dashboard-text">
      FeliksBlogManagementSystem
    </div>
    <div>
      这是我的博客管理系统
    </div>
    <div>
      微信id:Feliks13609777573
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
