
# Easy-less

为了少敲重复代码,节约时间,快速开发样式;


-----

# logo

![演示Demo](images/taro.png)


---

# 代码片段

- `absolute-aligned`

```javascript
 position: absolute;
 left: 0px;
 right: 0px;
 top: 0px;
 bottom: 0px;
 margin: auto;

```


- `border-tb`

```javascript
 border-top: @n solid @color;
 border-bottom: @n solid @color;

```

- `border-lr`

```javascript
 border-left: @n solid @color;
 border-right: @n solid @color;

```

- `margin-tb`

```javascript
 margin-top: @n;
 margin-bottom: @n;

```

- `margin-lr`

```javascript
 margin-left: @n;
 margin-right: @n;

```

- `padding-tb`

```javascript
 padding-top: @n;
 padding-bottom: @n;

```

- `padding-lr`

```javascript
 padding-left: @n;
 padding-right: @n;

```

- `font-YaHei`

```javascript
 font-family: MicrosoftYaHeiUI;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `font-ArialMT`

```javascript
 font-family: ArialMT;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `font-pf-medium`

```javascript
 font-family: PingFangSC-Medium;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `font-pf-Regular`

```javascript
 font-family: PingFangSC-Regular;
 font-size: ${1:@f}px;
 color: ${2:@c};

```

- `lh`

```javascript
 height: ${1:@h}px;
 line-height: ${2:@h}px;

```

- `posAbsolute`

```javascript
 position: absolute;
 top: ${@t}px;
 right: ${@r}px;
 bottom: ${@b}px;
 left: ${@l}px;

```

- `textflow`

```javascript
 white-space: nowrap;
 overflow: hidden;
 text-overflow: ellipsis;
 max-width: 100%;

```

- `dialog-mask`

```javascript
 opacity: 0.8;
 background: #000000;
 width: 100%;
 height: 100%;

```

- `dialog-mask-box`

```javascript
 position: fixed;
 z-index: 1000;
 left: 0px;
 right: 0px;
 top: 0px;
 bottom: 0px;

```

- `tf-aligned`

```javascript
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);

```

- `wh`

```javascript
 width: ${1:@h}px;
 height: %{2:@h}px;

```

- `bone-card`

```javascript
 background: ${1:#F4F4F4;}
 border-radius: ${2:8px;}
 width: ${3:@w}px;
 height: ${4:@h}px;

```

- `bone-box`

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

- `bone-disappear`

```javascript
 z-index: -1;
 opacity: 0;

```

