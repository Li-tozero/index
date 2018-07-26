<template>
  <div class="mod-home">
    <el-row gutter="10">
       <!-- 参数管理 -->
      <el-col :span="24">
        <el-card class="box-card parameter">
          <div class="content">
            <img src="../../assets/img/icons/参数管理.png">
            <div>parameter management</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">参数管理</a>
            </h1>
          </div>
        </el-card>
      </el-col>
      
    </el-row>
    <el-row gutter="10">
      <!-- 系统日志 -->
      <el-col :span="6">
        <el-card class="box-card diary">
          <div class="content">
            <i class="el-icon-document"></i>
            <div>diary management</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">系统日志</a>
            </h1>
          </div>
        </el-card>
      </el-col>
      <!-- 菜单管理 -->
      <el-col :span="12">
        <el-card class="box-card menu">
          <div class="content">
            <i class="el-icon-menu"></i>
            <div>menu management</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">菜单管理</a>
            </h1>
          </div>
        </el-card>
      </el-col>
      <!-- 文件上传 -->
      <el-col :span="6">
        <el-card class="box-card upload">
          <div class="content">
            <i class="el-icon-upload"></i>
            <div>file upload</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">文件上传</a>
            </h1>
          </div>
        </el-card>
      </el-col>
    </el-row>
     <el-row gutter="10">
      <!-- slq管理 -->
      <el-col :span="6">
        <el-card class="box-card diary sql">
          <div class="content">
            <img src="../../assets/img/icons/SQL监控.png">
            <div>sql monitor</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">SQL监控</a>
            </h1>
          </div>
        </el-card>
      </el-col>
      <!-- 定时任务 -->
      <el-col :span="6">
        <el-card class="box-card task">
          <div class="content">
            <img src="../../assets/img/icons/定时任务.png">
            <div>timed task</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">定时任务</a>
            </h1>
          </div>
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card class="box-card role">
          <div class="content">
            <img src="../../assets/img/icons/角色管理.png">
            <div>Role management</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">角色管理</a>
            </h1>
          </div>
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card class="box-card managers">
          <div class="content">
            <i class="el-icon-document"></i>
            <div>managers list</div>
          </div>
          <div class="content-wrap">
            <h1 class="entry-title">
              <a href="http://www.baidu.com" class="featured-image">管理员列表</a>
            </h1>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>
<script>

</script>
<style scoped>
*{
  margin:0;
  padding:0;
}
.box-card{
  position:relative;
  border-radius:0 0 0 0;
  color:#fff;
  text-transform: uppercase;
}
.parameter{
  background:#58d68d;
}
.diary{
  background:#00b6de;
}
.menu{
  background:#56dea7;
}
.upload{
  background:#ff7659;
}
.sql{
  background:#f8cd36;
}
.content{
  text-align:center;
}
.managers{
  background:#f26175;
}
.task{
  background:#5ca7df;
}
.role{
  background:#9e7ac2;
}
i{
  font-size:40px;
  margin:34px;
}
img{
  margin:34px;
}
.content-wrap{
  padding: 0;
  position: absolute;
  text-align: center;
  width: 100%;
  top: 0;
  bottom: 0;
  left:0;
  right:0;
  display: table-cell;
  vertical-align: middle;
}
.content-wrap h1.entry-title {
  display: table;
  font-size: 110%;
  height: 100%;
  width: 100%;
  margin:0;
}
.featured-image {
  display: table-cell;
  position: relative;
  transition: opacity .25s ease-in-out, background .25s ease-in-out;
  -moz-transition: opacity .25s ease-in-out, background .25s ease-in-out;
  -webkit-transition: opacity .25s ease-in-out, background .25s ease-in-out;
  vertical-align: middle;
  color: #fff;
  text-decoration: none;
  opacity: 0;
}
.featured-image:hover {
  opacity: 0.9;
  color: #fff;
  background: rgba(0,0,0,0.8);
}
</style>


