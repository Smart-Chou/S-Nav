# S-Nav/简单导航

**Just want to make a simple navigation website.**

用惯了各种导航首页，满屏幕尽是各种不厌其烦的广告和资讯；尝试自己写个自己的主页。不是镜像不是代理，就当做浏览器主页使用，支持自适应屏幕。  

---

## Demo

地址：[点击跳转](https://nav.kksan.top/)

---

## 响应式

### **桌面端**

![桌面端预览](https://s1.ax1x.com/2020/03/13/8MV3uT.png)

### **移动端**

![移动端预览](https://s1.ax1x.com/2020/03/14/8MV6Ve.jpg)

## GIF示例效果

![简单搜索](https://i.loli.net/2021/01/19/JsV34pBOcTbZk79.gif)

> （图片效果，以实际页面为准）

---

## 组件

### 图标

图标调用了阿里的图标`https://www.iconfont.cn/`，提供下本地包[点击下载](https://cdn.jsdelivr.net/gh/5iux/sou/icon.zip)  
嫌麻烦的可以使用js版本示例里面的`font-awesome`  

### 天气组件  

- Bootstrap：<https://getbootstrap.com/>
- CSSFX：<https://cssfx.netlify.com/>
- jQuery：<https://jquery.com/>
- slideout：<https://slideout.js.org/>
- font-awesome：<https://fontawesome.com/>
- 知心天气：<https://www.seniverse.com/>
- 天气API地址: <https://dev.qweather.com/widget/>

### 背景图

已默认添加随机加载bing背景，不需要刻意在index.php中删除；

如使用自定义背景，可以删除bing背景后在页面内添加以下代码：

```html
<style> 
   body{background:url("https://cn.bing.com//th?id=OHR.HuntsMesa_JA-JP3140979616_1920x1080.jpg&rf=LaDigue_1920x1080.jpg&pid=hp") no-repeat center/cover;}
</style>
```
