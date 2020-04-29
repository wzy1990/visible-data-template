# 数据可视化开发与设计
	应对现在数据可视化的趋势，越来越多企业需要在很多厂家（营销数据，生产数据，用户数据）下使用，可视化图表来展示体现数据，让数据更加直观，数据特点更加突出。

## 01.使用技术
完成该项目需要具备以下知识：
- div+css 布局
- flex布局
- sass
- 原生js + jQuery使用
- rem适配
- echarts基础

## 02.案例适配方案
- 设计稿是1920px
- flexible.js 把屏幕分割成24等份
- cssrem 插件的基准值设为80px

## 03.基础设置
- body 设置背景图，缩放为100%,行高1.15
- css 初始化

## 04.header布局
- 高度为100px
- 背景图，在容器内显示
- 缩放比例为100%
- h1标题部分 白色， 38像素 居中显示，行高为80px
- 时间模块 定位右侧right为30px，行高为75px, 文字颜色：rgba(255, 255, 255, 0.7),而文字大小为20像素

```js
async function timeout (ms) {
  await new Promise((resolve) => {
    setTimeout(resolve, ms)    
  })
}
```