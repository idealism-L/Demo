<template>
  <div class="app-container home">
    <el-row :gutter="20">
      <!-- 左侧部分 -->
      <el-col :sm="24" :lg="12" class="left-column">
        <h2>后台管理框架</h2>
      </el-col>

      <!-- 右侧部分 -->
      <el-col :sm="24" :lg="12" class="right-column">
        <h2>技术选型</h2>
        <el-row>
          <!-- 后端技术 -->
          <el-col :span="12">
            <h4>后端技术</h4>
            <ul>
              <li>SpringBoot</li>
              <li>Spring Security</li>
              <li>JWT</li>
              <li>MyBatis</li>
              <li>Druid</li>
              <li>Fastjson</li>
              <li>...</li>
            </ul>
          </el-col>

          <!-- 前端技术 -->
          <el-col :span="12">
            <h4>前端技术</h4>
            <ul>
              <li>Vue</li>
              <li>Vuex</li>
              <li>Element-ui</li>
              <li>Axios</li>
              <li>Sass</li>
              <li>Quill</li>
              <li>...</li>
            </ul>
          </el-col>
        </el-row>
      </el-col>
    </el-row>
    <el-divider />
  </div>
</template>

<script>
export default {
  name: "Index",
  data() {
    return {
      // 页面版本号
      version: "3.8.9",
    };
  },
};
</script>

<style scoped lang="scss">
.home {
  font-family: "open sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  color: #676a6c;
  overflow-x: hidden;

  ul {
    padding: 0;
    margin: 0;
    list-style-type: none;
  }

  h4 {
    margin-top: 0;
  }

  h2 {
    margin-top: 10px;
    font-size: 26px;
    font-weight: 100;
  }

  .left-column {
    padding-left: 20px;
  }

  .right-column {
    padding-left: 50px;
  }
}
</style>
