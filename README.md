
# Easy-less

为了少敲重复代码,节约时间,快速开发样式;
如果大家有开发过程中好用的样式 欢迎提merage 

----

[提merage请点我](https://github.com/lemondreamtobe/Easy-less)

[![Version](https://vsmarketplacebadge.apphb.com/version/LemonZhang.easy-less.svg)](https://marketplace.visualstudio.com/items?itemName=LemonZhang.easy-less) [![Install](https://vsmarketplacebadge.apphb.com/installs-short/LemonZhang.easy-less.svg)](https://marketplace.visualstudio.com/items?itemName=LemonZhang.easy-less)

-----

# 效果

![演示Demo](image/demo.gif)


-----

# logo

![演示Demo](image/taro.png)


---

# 代码片段

- `absolute-aligned` 绝对定位水平垂直居中

```javascript
 position: absolute;
 left: 0px;
 right: 0px;
 top: 0px;
 bottom: 0px;
 margin: auto;

```


- `border-tb` 上下边框设置

```javascript
 border-top: @n solid @color;
 border-bottom: @n solid @color;

```

- `border-lr` 左右边框设置

```javascript
 border-left: @n solid @color;
 border-right: @n solid @color;

```

- `margin-tb` 上下边距设置

```javascript
 margin-top: @n;
 margin-bottom: @n;

```

- `margin-lr` 左右边距设置

```javascript
 margin-left: @n;
 margin-right: @n;

```

- `padding-tb` 上下内边距设置

```javascript
 padding-top: @n;
 padding-bottom: @n;

```

- `padding-lr` 左右内边距设置

```javascript
 padding-left: @n;
 padding-right: @n;

```

- `font-YaHei` 微软雅黑字体

```javascript
 font-family: MicrosoftYaHeiUI;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `font-ArialMT` ArialMT字体

```javascript
 font-family: ArialMT;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `font-pf-medium` 平方宋字体-细体

```javascript
 font-family: PingFangSC-Medium;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `font-pf-Regular` 平方宋字体-regular

```javascript
 font-family: PingFangSC-Regular;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `lh` 快速设置行高

```javascript
 height: ${1:@h}px;
 line-height: ${2:@h}px;

```

- `posAbsolute` 快速绝对定位

```javascript
 position: absolute;
 top: ${@t}px;
 right: ${@r}px;
 bottom: ${@b}px;
 left: ${@l}px;

```

- `textflow` 文本溢出

```javascript
 white-space: nowrap;
 overflow: hidden;
 text-overflow: ellipsis;
 max-width: 100%;

```

- `dialog-mask` 弹窗遮罩

```javascript
 opacity: 0.8;
 background: #000000;
 width: 100%;
 height: 100%;

```

- `dialog-mask-box` 弹窗遮罩父级

```javascript
 position: fixed;
 z-index: 1000;
 left: 0px;
 right: 0px;
 top: 0px;
 bottom: 0px;

```

- `tf-aligned` tansform的水平垂直居中

```javascript
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);

```

- `wh` 快速设置宽高

```javascript
 width: ${1:@h}px;
 height: ${2:@h}px;

```

- `bone-card` 骨架图卡片

```javascript
 background: ${1:#F4F4F4;}
 border-radius: ${2:8px;}
 width: ${3:@w}px;
 height: ${4:@h}px;

```

- `bone-box` 骨架图盒子

```javascript
  position: fixed;
  z-index: 9999;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  font-size: 0px;
  background: #ffffff;
  opacity: 1;
  transition: all 1s ease;
```

- `bone-disappear` 骨架图消失动效

```javascript
 z-index: -1;
 opacity: 0;

```

