pages
utils
json文件
app.json:
{
  "pages":[ 
    "pages/index/index",
    "pages/logs/logs"
  ],
  "window":{
    "backgroundTextStyle":"light",
    "navigationBarBackgroundColor": "#fff",
    "navigationBarTitleText": "Weixin",
    "navigationBarTextStyle":"black"
  },
  "style": "v2",
  "sitemapLocation": "sitemap.json"
}

标签名称不同
html: div, span, img, a
wxml: view, text, image, navigator

属性节点不同
<a href="#"></a>
<navigator url="/pages/home/home"></navigator>

提供类似vue的模板语法
数据绑定
列表渲染
条件渲染

宿主环境：通信模型；运行机制；组件；API

组件分成9类：
视图容器；view;scroll-view；swiper；swapper-item
基础内容；Text；Icon；Image；Button；Progress；
表单组件；Input；Label；Checkbox；Radio；Picker；Switch；Slider；Textarea；Keyboard
导航组件；Navigator；
基础内容；表单控件；导航组件；媒体组件；map地图组件；canvas画布组件；开放能力；无状态组件；无障碍

https://www.bilibili.com/video/BV1834y1676P?p=8&vd_source=42b9f505ad9c231fafdb3ac659b939e6