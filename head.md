### 网页head(含常用meta标签)  
  
```html
<!--声明编码-->
<meta charset="utf-8">
<!--网页标题-->
<title>网页标题</title>
<!--重定向或刷新-->
<!--
<meta http-equiv="refresh" content="0;url=">
-->
<!--关键字-->
<meta name="keywords" content="关键字1,关键字2">
<!--描述-->
<meta name="description" content="描述">
<!--视口：优化移动浏览器的显示，响应式网站-->
<meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1,user-scalable=no">
<!--忽略识别电话号码、邮箱、地址-->
<meta name="format-detection" content="telephone=no,email=no,adress=no">
<!--搜索引擎索引方式-->
<!--
all：文件将被检索，且页面上的链接可以被查询；
none：文件将不被检索，且页面上的链接不可以被查询；
index：文件将被检索；
follow：页面上的链接可以被查询；
noindex：文件将不被检索；
nofollow：页面上的链接不可以被查询。
-->
<meta name="robots" content="index,follow">
<!--DNS预解析，可使用双斜杆自适应协议-->
<link rel="dns-prefetch" href="//预解析网址">
<!--苹果App广告条-->
<meta name="apple-itunes-app" content="app-id=苹果AppStoreID">
<!--浏览器何种内核渲染-->
<meta name="renderer" content="webkit">
<!--禁止百度转码-->
<meta http-equiv="Cache-Control" content="no-transform">
<!--电脑网页-手机网页的对应关系-->
<meta http-equiv="mobile-agent" content="format=html5;url=手机网页网址(含协议)">
<!--添加到主屏后的标题-->
<meta name="apple-mobile-web-app-title" content="标题">
<!--WebApp全屏模式-->
<meta name="apple-mobile-web-app-capable" content="yes">
<!--UC浏览器强制全屏-->
<meta name="full-screen" content="yes">
<!--UC浏览器应用模式-->
<meta name="browsermode" content="application">
<!--QQ浏览器强制全屏-->
<meta name="x5-fullscreen" content="true">
<!--QQ浏览器应用模式-->
<meta name="x5-page-mode" content="app">
```