<template>
  <div class="layout">
    <el-container>
      <el-aside width="200px">
        <SideBar/>
      </el-aside>
      <el-container>
        <el-header>Header</el-header>
        <el-main>
          <router-view></router-view>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script setup lang="ts">
</script>

<style lang="less" scoped>
.layout{
  height: 100%;
  .el-container{
    height: 100%;
  }
}
</style>