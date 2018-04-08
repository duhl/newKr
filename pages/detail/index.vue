<template>
    <div>
        <header-box/>
        <div class="breadcrumb">
            <el-breadcrumb separator-class="el-icon-arrow-right">
            <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
            <el-breadcrumb-item>活动管理</el-breadcrumb-item>
            <el-breadcrumb-item>活动列表</el-breadcrumb-item>
            <el-breadcrumb-item>活动详情</el-breadcrumb-item>
            </el-breadcrumb>
        </div>
        <div class="intro-box">

        </div>
        <div class="video-box">

        </div>
        <footer-box/>
    </div>
</template>
<script>
import HeaderBox from "~/components/HeaderBox.vue";
import FooterBox from "~/components/FooterBox.vue";
export default {
  data() {
    return {};
  },
  components: {
    HeaderBox,
    FooterBox
  }
};
</script>
<style lang="less" scoped>
.breadcrumb {
  width: 1000px;
  margin: 20px auto;
}
.intro-box {
  width: 1000px;
  height: 500px;
  margin: 20px auto;
  background: white;
  border-radius: 4px;
}
.video-box {
  width: 1000px;
  height: 500px;
  margin: 20px auto;
  background: white;
  border-radius: 4px;
}
</style>
