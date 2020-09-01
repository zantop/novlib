---
title: API
---

## telStar

隐藏手机号

```js
import { telStart } from 'novlib';

telStar(17621989037); //176****9037
```

## floatNum

`floatNum(num,dot)`

保留几位小数，默认整数，第二个参数保留小数的位数

```js
import { floatNum } from 'novlib';

floatNum(12.0637); //12
floatNum(12.0637，3); //12.064
```

## randomBetween

`randomBetween(m,n)`

指定范围内生成随机数，包含最小值，不包含最大值

```js
randomBetween(3, 1); //随机数可是 1 2
randomBetween(1, 3); //随机数可是 1 2
```

## scrollToTop

函数返回顶部

```js
scrollToTop();
```

## smoothScroll

`smoothScroll(class?id)`

平滑滚动到指定元素浏览器窗口的可见区域

```js
//如滚动到ID为nav的元素
smoothScroll('#nav');
```

## isEmpty

`isEmpty(Array?Object)`

检测数组或对象是否为空

```js
console.log(isEmpty([])); //true
console.log(isEmpty({})); //true
```

## getQueryString

`getQueryString(name,?url)` url 默认 `window.location.href`

获取 URL 后参数值

```js
getQueryString(a, 'https://www.google.com/?a=123'); //123
```

## isWeiXin

是否微信浏览器,`isWeiXin()`返回值 true/false

## device

判断手机设备，`device()`返回值`ANDROID`/`IOS`
