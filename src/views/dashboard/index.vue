<template>
  <div class="dashboard-container">
    <div class="dashboard-text">我的Tina啊首页用户名字子: {{ name }}</div>
    <div class="dashboard-text">测试loongzhang首页用户名字子: {{ name }}</div>
    <div>我是主分支新家内容  主分支9999</div>

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
