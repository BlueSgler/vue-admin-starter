<template>
  <div id="header">
    <el-row>
      <el-col :span="12" class="title">AdminStater</el-col>
      <el-col :span="12" class="header-right">
        <el-icon :size="20" class="bell"><Bell /></el-icon>
        <el-avatar :size="40" class="avater" />
      </el-col>
    </el-row>
    
  </div>
</template>

<script setup lang='ts'>
import { Bell } from '@element-plus/icons-vue'
</script>

<style lang='scss' scoped>
#header {
  color: #fff;
  .title {
     font-size: 22px;
     line-height: 60px;
     color: #35c3f3;
  }
  .header-right {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    .bell {
      margin-right: 20px;
      cursor: pointer;
    }
    .avater {
      cursor: pointer;
    }
  }
}
</style>