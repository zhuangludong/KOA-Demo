<template>
  <el-container>
    <el-header class="page-header">湘湘仓储管理系统 </el-header>
    <el-main
      ><el-menu
        :default-active="activeIndex"
        class="el-menu-demo"
        mode="horizontal"
        @select="handleSelect"
        background-color="#545c64"
        text-color="#fff"
        active-text-color="#ffd04b"
      >
        <el-menu-item index="1">处理中心</el-menu-item>
        <el-menu-item index="3" disabled>我不能点</el-menu-item>
      </el-menu>
    </el-main>
  </el-container>
</template>

<script>
export default {
  data () {
    return {
      activeIndex: '1',
    }
  }
}
</script>

<style lang='scss' scoped>
.page-header {
  color: aquamarine;
  .hahah {
    color: red;
  }
}
</style>