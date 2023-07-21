<template>
  <div class="common-layout">
      <el-container>
        <el-header>
          <AdminHeader></AdminHeader>
        </el-header>
        <el-container>
          <el-aside width="200px">Aside</el-aside>
          <el-main>Main</el-main>
        </el-container>
      </el-container>
    </div>
</template>

<script setup lang='ts'>
import AdminHeader from '@/components/layout/AdminHeader.vue'
</script>

<style lang='scss' scoped>

.common-layout {
  min-height: 100vh;
  background-color: #141318;
}
.el-header {
  background-color: #000000;
}

.el-aside {
  background-color: skyblue;
}

.el-main {
  background-color: orchid;
}
</style>