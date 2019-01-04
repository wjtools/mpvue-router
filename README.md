# mpvue-router
> 在 mpvue 中使用类 vue-router 的路由写法<br>
> 基于 [mpvue-router-patch](https://github.com/F-loat/mpvue-router-patch#readme)，感谢原作者！<br>
> 修复返回上一页后 $route.query 取值为空的问题，以及一些定制功能

## 安装

``` bash
npm i mpvue-router
```

## 使用

``` js
// main.js
import Vue from 'vue'
import MpvueRouter from 'mpvue-router'

Vue.use(MpvueRouter)
```

## API

> 用法与 [mpvue-router-patch](https://github.com/F-loat/mpvue-router-patch#readme) 相同
