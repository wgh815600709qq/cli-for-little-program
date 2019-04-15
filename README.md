# 小程序快速开发架构

## version v1.0.0

## 业务架构
    └──assets 静态资源库
    ├──libs   第三方相关库
        └──  有赞UI组件库vant
        └──  echarts图表库  [https://github.com/ecomfe/echarts-for-weixin]
    ├──components 公用组件（全局性质）
    ├──pages   页面入口
        └── 业务模块1
        ├── 业务模块2
        ├── 业务模块3
        ├── 业务模块4
        ├──Entrys  入口类
        └──Test  测试类(嵌套深页面,调试组件入口)
    └──utils  工具类

## 手机代理相关[内网开发]
    1、电脑连接内网;
    2、fiddler开启8888端口的监听；（调试小程序时候把Capture Https Connects 不能带上）;
    3、手机代理《电脑ip：8000》;
    4、手机访问ip：《8000下载证书》;

## 问题点

## 发布须知

## 版本迭代记录

## env相关
   env.config.json配置环境差异变量.
   
