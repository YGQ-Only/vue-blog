<template>
  <div>
    <!-- 面包屑导航 -->
    <el-breadcrumb separator-class="el-icon-arrow-right">
      <el-breadcrumb-item :to="{ path: '/admin' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>用户管理</el-breadcrumb-item>
      <el-breadcrumb-item>用户列表</el-breadcrumb-item>
    </el-breadcrumb>
    <UserContent></UserContent>
  </div>
</template>

<script>
import UserContent from "./childComps/UserContent";

export default {
  name: "User",
  components: {
    UserContent
  },
  data() {
    return {};
  },
  created() {}
};
</script>

<style lang="less" scoped>

</style>
