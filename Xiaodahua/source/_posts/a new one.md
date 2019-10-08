---
title: Axios-源码分析
cover_picture: https://i.imgur.com/jHfmZxo.jpg 
date: 2017-11-30 10:52:27
categories: axios
tags: axios
---
![](https://i.imgur.com/5CJJNmY.jpg)
Axios 可以说是当前 Github 上最受关注的 HTTP 库，目前已经有超过 25k 的 star 数。作为 vue.js 官方推荐的 HTTP 库，必然有着过人之处。

Axios 的主要特性包括：

基于 Promise
支持浏览器和 node.js
可添加拦截器和转换请求和响应数据
请求可以取消
自动转换 JSON 数据
客户端支持防范 XSRF
支持各主流浏览器及 IE8+
对比于 fetch，除了同样支持 Promise API 外，aixos 的确拥有更加丰富的功能，而这次的源码分析也主要是针对‘拦截器’和‘请求取消’。


   
 
