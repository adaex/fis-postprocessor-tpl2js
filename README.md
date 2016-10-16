# fis-postprocessor-tpl2js
将html模板转换成js模块

## 安装
支持全局安装和局部安装，根据自己的需求来定。

```bash
npm install fis-postprocessor-tpl2js
```

## 使用

```javascript
fis.match('*.tpl', {
    postprocessor: fis.plugin('tpl2js'),
    isHtmlLike: true,
    rExt: '.js'
});
```