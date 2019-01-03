1.安装wechat_devtools_1.02.1810250_x64.exe
2.微信web开发者工具安装后，运行微信开发者工具
3.选择小程序项目，点击新建，代码片段目录选择压缩包下的Map文件夹，（定义代码片段名称、填写APPID），点击新建
APPID：wx2fd6fcc3d4a9a059
4.修改app.json文件，在pages字段中将“index/index”删除，修改
"pages":[
    "pages/index/index",
    "map/map",
    "poi/poi"
  ],
5.文件目录说明
app.json 当前小程序的全局配置，包含了小程序所有页面路径
.wxml wxml文件定义小程序页面布局
.js js文件定义用户相关操作事件(交互逻辑)
.wxss wxss文件定义当前小程序页面的局部页面样式