## WebDesktop说明
2011年作品，基于网上流传的源码修改，采用JavaScript+Css+Html实现webos的效果，已不再维护

## 截图

![webdesktop](https://github.com/anruyi/anruyi.github.io/blob/master/webdesktop-preview.png)

## 示例

[CY](http://blog.ciqufu.com?_blank)

var aTagArr = [].slice.apply(document.getElementsByTagName("a"));

aTagArr.forEach(function (e, i) {
  e.href.indexOf("_blank") > -1 ? e.target = "_blank" : null;
});




