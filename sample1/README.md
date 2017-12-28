# Donate-Page

一款捐赠按钮样式，包含PayPal、支付宝、微信，可使用iframe直接嵌入，方便简洁。

**Demo在线演示：**

[在线演示1](https://yojoy.top/donate-page/) [在线演示2](https://gitcdn.link/cdn/TinyJay/donate-page/faa9d69210d334af644f254296e1a8b3e24da3be/simple/index.html)

![GIF动态效果图](https://upload-images.jianshu.io/upload_images/1819713-518ef42c3301b2fa.gif?imageMogr2/auto-orient/strip%7CimageView2/2/w/420/format/webp)

#### 设置PayPal账户

```
/script.js:4-6 对应账户的二维码路径
/index.html:28 PayPal.me 改为现在收款页面，这样可以删除原来的按钮方式了。
```

> 针对不同项目可以直接在 URL 加入项目参数和金额，不过仅仅作用于 PayPal 方式

```
https://yojoy.top/donate-page/sample1/index.html?item='donate-page&price=2'
```

#### iframe引入
> 使用 `iframe` 嵌入页面的代码，高度至少 `240px`，宽度至少 `310px`！

```
<iframe src="https://yojoy.top/donate-page/sample1/index.html" style="overflow-x:hidden;overflow-y:hidden; border:0xp none #fff; min-height:240px; width:100%;"  frameborder="0" scrolling="no"></iframe>
```

### License

Released under the MIT license.