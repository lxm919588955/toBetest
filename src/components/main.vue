<template>
  <div class="main">
    <el-row>
      <el-button>默认按钮</el-button>
      <el-button type="primary">主要按钮</el-button>
      <el-button type="success">成功按钮</el-button>
      <el-button type="info">信息按钮</el-button>
      <el-button type="warning">警告按钮</el-button>
      <el-button type="danger">危险按钮</el-button>
    </el-row>
  </div>
</template>

<script>
export default {
  name: 'main'
}
</script>

<style lang="scss" scoped>
.main{
  width: 375px;
  height: 100px;
  background: aqua;
  span{
    font-size: 24px;
  }
}
</style>
