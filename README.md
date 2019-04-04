# postcss-svg-hairlines

## usage
- 安装插件
```$xslt
npm install postcss-svg-hairlines --save-dev
```
- 在postcss.config.js 中配置
````$xslt
module.exports = {
    'postcss-svg-hairlines': {
        base64: true,
        blackList: [ignore] // 忽略不需要转义的样式名称
    }
}
````
