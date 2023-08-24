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