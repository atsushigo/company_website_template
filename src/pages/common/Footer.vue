<template>
  <el-container id="footer">
    <el-footer height="10rem">
      COPYRIGHT By Sam © 2024
    </el-footer>
  </el-container>
</template>

<script>
export default {
  name: 'MainFooter'
}
</script>

<style scoped>
  #footer {
    background-color: #2c3e50;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  #footer footer {
    height: 10rem;
    line-height: 10rem;
  }
</style>
