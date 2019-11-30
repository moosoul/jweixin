# 微信官网 JSSDK 的 npm 包

## 支持 CommonJS, 方便 Webpack 直接使用

- [jweixin-1.4.0.js](http://res.wx.qq.com/open/js/jweixin-1.4.0.js)
- [微信 JSSDK 文档](https://developers.weixin.qq.com/doc/offiaccount/OA_Web_Apps/JS-SDK.html)

## 使用方法

### npm

```bash
npm install --save https://github.com/moosoul/jweixin.git
```

### yarn

```bash
yarn add https://github.com/moosoul/jweixin.git
```

### 前端代码

```javascript
import { wx } from "jweixin";
wx.config({
  debug: process.env.NODE_ENV === "development",
  ...params
});
```
