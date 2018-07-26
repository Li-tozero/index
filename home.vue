<template>
  <div class="mod-home">
    <el-row gutter="10">
      <!-- 左边一列 -->
      <el-col :xs="24" :lg="16">
        <!-- 人才招聘部分 -->
        <el-row gutter="10">
          <el-col :xs="24" :lg="12">
            <a class="comA" href="#">
              <el-card class="box-card wanted">
                <span>
                <img src="../../assets/img/icons/人才招聘.png"/>
                </span>
              <span class="comFont">人才招聘</span>
            </el-card>
            </a>
          </el-col>
          <!-- 用户管理部分 -->
          <el-col :xs="24" :lg="12">
            <a class="comA" href="#">
              <el-card class="box-card manage">
                <span>
                <img src="../../assets/img/icons/用户管理.png"/>
                </span>
              <span class="comFont">用户管理</span>
            </el-card>
            </a>
          </el-col>
        </el-row>
        <el-row gutter="10">
          <!-- 企业社区部分 -->
          <el-col :xs="24" :lg="12">
            <a class="comA" href="#">
              <el-card class="box-card enterpriceCommunity">
                <span>
                <img src="../../assets/img/icons/企业社区.png"/>
                </span>
              <span class="comFont">企业社区</span>
            </el-card>
            </a>
          </el-col>
          <!-- 版本信息部分 -->
          <el-col :xs="24" :lg="12">
            <a class="comA" href="#">
              <el-card class="box-card version">
                <span>
                <img src="../../assets/img/icons/版本信息.png"/>
                </span>
              <span class="comFont">版本信息</span>
            </el-card>
            </a>
          </el-col>
        </el-row>
        <el-row gutter="10">
          <el-col :xs="24" :lg="12">
            <el-card class="box-card" shadow="hover">
              <div slot="header" class="clearfix">
                <img src="../../assets/img/icons/任务中心.png" style="width:14px;"/>
                <span>任务中心</span>
              </div>
              <div v-for="o in 4" :key="o" class="text item">
                {{'列表内容'+o}}
              </div>
            </el-card>
          </el-col>
          <el-col :xs="24" :lg="12">
            <el-card class="box-card" shadow="hover">
              <div slot="header" class="clearfix">
                <img src="../../assets/img/icons/人才招聘.png" style="width:14px;"/>
                <span>人才招聘</span>
              </div>
              <div v-for="o in 4" :key="o" class="text item">
                {{'列表内容'+o}}
              </div>
            </el-card>
          </el-col>
        </el-row>
        <!-- 产品动态选项卡开始部分 -->
        <el-row gutter="10" class="productionMsg">
          <el-col :xs="24" :lg="12">
            <el-tabs type="border-card">
            <el-tab-pane>
            <span slot="label"><img src="../../assets/img/icons/产品动态.png" style="width:14px;"/>产品动态</span>
            <ul>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
            </ul>
            </el-tab-pane>
            <el-tab-pane>
              <span slot="label"><img src="../../assets/img/icons/更多.png" style="width:14px;"/> 更多</span>
              <ul>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
              </ul>
            </el-tab-pane>
            </el-tabs>
          </el-col>
          <el-col :xs="24" :lg="12">
            <el-tabs type="border-card" style="border-radius:0 0 5px 5px;">
            <el-tab-pane>
            <span slot="label"><img src="../../assets/img/icons/产品动态.png" style="width:14px;"/>产品动态</span>
            <ul>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
            </ul>
            </el-tab-pane>
            <el-tab-pane>
              <span slot="label"><img src="../../assets/img/icons/更多.png" style="width:14px;"/> 更多</span>
              <ul>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
              </ul>
            </el-tab-pane>
            </el-tabs>
          </el-col>
        </el-row>
        <!-- 产品动态选项卡结束部分 -->
        <!-- 四小格部分 -->
        <el-row gutter="10" style="margin-top:10px;">
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <span>
                <img src="../../assets/img/icons/人才招聘.png"/>
                </span>
              <span>人才招聘</span>
            </el-card>
            </a>
          </el-col>
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <span>
                <img src="../../assets/img/icons/人才招聘.png"/>
                </span>
              <span>人才招聘</span>
            </el-card>
            </a>
          </el-col>
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <span>
                <img src="../../assets/img/icons/人才招聘.png"/>
                </span>
              <span>人才招聘</span>
            </el-card>
            </a>
          </el-col>
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <span>
                <img src="../../assets/img/icons/人才招聘.png"/>
                </span>
              <span>人才招聘</span>
            </el-card>
            </a>
          </el-col>
        </el-row>
        <!-- 四小格部分 -->
        <el-row gutter="10" style="margin-top:10px;">
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <div style="text-align:center">
                <img src="../../assets/img/icons/人才招聘.png"/>
                </div>
                <br/>
                <div style="text-align:center">
                  <span>人才招聘</span><br/><br/>
                  <span>招聘人数：4</span>
                </div>
            </el-card>
            </a>
          </el-col>
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <div style="text-align:center">
                <img src="../../assets/img/icons/人才招聘.png"/>
                </div>
                <br/>
                <div style="text-align:center">
                  <span>人才招聘</span><br/><br/>
                  <span>招聘人数：4</span>
                </div>
            </el-card>
            </a>
          </el-col>
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <div style="text-align:center">
                <img src="../../assets/img/icons/人才招聘.png"/>
                </div>
                <br/>
                <div style="text-align:center">
                  <span>人才招聘</span><br/><br/>
                  <span>招聘人数：4</span>
                </div>
            </el-card>
            </a>
          </el-col>
          <el-col :span="6">
            <a href="#" class="comA">
              <el-card class="box-card wanted">
                <div style="text-align:center">
                <img src="../../assets/img/icons/人才招聘.png"/>
                </div>
                <br/>
                <div style="text-align:center">
                  <span>人才招聘</span><br/><br/>
                  <span>招聘人数：4</span>
                </div>
            </el-card>
            </a>
          </el-col>
        </el-row>
        <el-row>
          <el-col :span="12">
            <div id="myChart" :style="{width: '300px', height: '300px'}"></div>
          </el-col>
          <el-col :span="12">
            <div id="myChart2" :style="{width: '300px', height: '300px'}"></div>
          </el-col>
        </el-row>
      </el-col>
      <!-- 右边一列 -->
      <el-col :xs="24" :lg="8">
        <!-- 项目管理开始部分 -->
        <el-row gutter="10">
          <el-col :span="24">
            <el-card class="box-card" shadow="hover">
              <div slot="header" class="clearfix">
                <img src="../../assets/img/icons/项目管理.png" style="width:14px;"/>
                <span>项目管理</span>
              </div>
              <ul>
                <li><a href="#">项目管理1，项目管理1</a></li>
                <li><a href="#">项目管理1</a></li>
                <li><a href="#">项目管理1</a></li>
                <li><a href="#">项目管理1</a></li>
                <li><a href="#">项目管理1</a></li>
                <li><a href="#">项目管理1</a></li>
              </ul>
            </el-card>
          </el-col>
        </el-row>
        <!-- 项目管理结束部分 -->
        <!-- 交流园地开始部分 -->
        <el-row gutter="10" class="contact">
          <el-col :span="24">
            <el-card class="box-card" shadow="hover">
              <div slot="header" class="clearfix">
                <img src="../../assets/img/icons/交流园地.png" style="width:14px;"/>
                <span>交流园地</span>
              </div>
              <ul>
                <li><a href="#">问题1的解答，问题1的解答</a></li>
                <li><a href="#">问题1的解答</a></li>
                <li><a href="#">问题1的解答</a></li>
                <li><a href="#">问题1的解答</a></li>
                <li><a href="#">问题1的解答</a></li>
                <li><a href="#">问题1的解答</a></li>
              </ul>
            </el-card>
          </el-col>
        </el-row>
        <!-- 交流园地结束部分 -->
        <!-- 档案管理开始部分 -->
        <el-row gutter="10">
          <el-col :span="24">
            <el-card class="box-card" shadow="hover">
              <div slot="header" class="clearfix">
                <i class="el-icon-document"></i>
                <span>档案管理</span>
              </div>
              <div v-for="o in 4" :key="o" class="text item">
                {{'列表内容'+o}}
              </div>
            </el-card>
          </el-col>
        </el-row>
        <!-- 档案管理结束部分 -->
        <!-- 联系我们开始部分 -->
        <el-row gutter="10">
          <el-col :span="24">
            <el-card class="box-card" shadow="hover">
              <div slot="header" class="clearfix">
                <i class="el-icon-phone"></i>
                <span>联系我们</span>
              </div>
              <div v-for="o in 4" :key="o" class="text item">
                {{'列表内容'+o}}
              </div>
            </el-card>
          </el-col>
        </el-row>
        <!-- 联系我们结束部分 -->
        <el-row>
           <el-col :span="24">
            <el-tabs type="border-card">
            <el-tab-pane style="margin-left:10px;">
            <span slot="label"><img src="../../assets/img/icons/产品动态.png" style="width:14px;"/>产品动态</span>
            <ul>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
                <li><a href="#">最新产品消息</a></li>
            </ul>
            </el-tab-pane>
            <el-tab-pane style="margin-left:10px;">
              <span slot="label"><img src="../../assets/img/icons/更多.png" style="width:14px;"/> 更多</span>
              <ul>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
                <li><a href="#">更多消息</a></li>
              </ul>
            </el-tab-pane>
            </el-tabs>
          </el-col>
        </el-row>
      </el-col>
    </el-row>
  </div>
</template>

<style>
/*
common style
*/
ul{
  margin:0;
  padding:0;
}
li{
  color:#7e7e7e;
  height:22px;
}
a{
  color:#7e7e7e;
  text-decoration:none;
}
a:hover{
  color:#b4b1b1;
  text-decoration: underline;
}
img{
  width:20%;
}
/*
左侧顶部四个的颜色设置
*/
.comFont{
  font-size:24px;
}
.wanted{
  background:#ff5722;
}
.wanted:hover{
  background:#ef6c43;
}
.manage{
  background:#1e9fff;
}
.manage:hover{
  background:#4badf7;
}
.enterpriceCommunity{
  background:#3ff31d;
}
.enterpriceCommunity:hover{
  background:#73f75a;
}
.version{
  background:#7c1eff;
}
.version:hover{
  background:#9250ef;
}
.comA:link{
  display:block;
  text-decoration:none;
}
.com:visited .com:hover{
  text-decoration: none;
}
.contact ul{
  list-style-type:square;
}
.productionMsg ul{
  list-style-type:none;
}
.el-col {
    border-radius: 4px;
  }
/*卡片中的内容*/
  .text {
    font-size: 14px;
  }

  .item {
    margin-bottom: 18px;
  }

  .clearfix:before,
  .clearfix:after {
    display: table;
    content: "";
  }
  .clearfix:after {
    clear: both
  }

  .box-card {
    /*width: 480px;*/
    margin-bottom:10px;
  }
</style>

<script>
// 引入基本模板
let echarts = require('echarts/lib/echarts')

// 引入柱状图组件
require('echarts/lib/chart/bar')
// 引入提示框和title组件
require('echarts/lib/component/tooltip')
  export default {
    mounted() {
    this.drawLine();
  },
  methods: {
    drawLine() {
      // 基于准备好的dom，初始化echarts实例
      let myChart = echarts.init(document.getElementById('myChart'));
      let myChart2= echarts.init(document.getElementById('myChart2'))
      // 绘制图表
      myChart.setOption({
        tooltip: {},
        xAxis: {
          data: ["PC端工程师", "后端工程师", "移动工程师", "维护人员", "产品经理", "管理人员"]
        },
        yAxis: {},
        series: [{
          name: '人数',
          type: 'bar',
          data: [5, 20, 36, 10, 10, 20]
        }]
      });

      //绘制图标2
      myChart2.setOption({

        tooltip : {
        trigger: 'axis',
        axisPointer : {            // 坐标轴指示器，坐标轴触发有效
            type : 'shadow'        // 默认为直线，可选为：'line' | 'shadow'
        },
        formatter: function (params) {
            var tar;
            if (params[1].value != '-') {
                tar = params[1];
            }
            else {
                tar = params[0];
            }
            return tar.name + '<br/>' + tar.seriesName + ' : ' + tar.value;
        }
    },
    legend: {
        data:['支出','收入']
    },
    grid: {
        left: '3%',
        right: '4%',
        bottom: '3%',
        containLabel: true
    },
    xAxis: {
        type : 'category',
        splitLine: {show:false},
        data :  function (){
            var list = [];
            for (var i = 1; i <= 11; i++) {
                list.push('11月' + i + '日');
            }
            return list;
        }()
    },
    yAxis: {
        type : 'value'
    },
    series: [
        {
            name: '辅助',
            type: 'bar',
            stack: '总量',
            itemStyle: {
                normal: {
                    barBorderColor: 'rgba(0,0,0,0)',
                    color: 'rgba(0,0,0,0)'
                },
                emphasis: {
                    barBorderColor: 'rgba(0,0,0,0)',
                    color: 'rgba(0,0,0,0)'
                }
            },
            data: [0, 900, 1245, 1530, 1376, 1376, 1511, 1689, 1856, 1495, 1292]
        },
        {
            name: '收入',
            type: 'bar',
            stack: '总量',
            label: {
                normal: {
                    show: true,
                    position: 'top'
                }
            },
            data: [900, 345, 393, '-', '-', 135, 178, 286, '-', '-', '-']
        },
        {
            name: '支出',
            type: 'bar',
            stack: '总量',
            label: {
                normal: {
                    show: true,
                    position: 'bottom'
                }
            },
            data: ['-', '-', '-', 108, 154, '-', '-', '-', 119, 361, 203]
        }
    ]


      })

  }
  }
}
</script>


