---
layout: post
title:  "Coding Post"
description: An example post which shows code rendering.
date:   2019-05-23 21:03:36 +0530
categories: Javascript NodeJS
---

安装glumpy:
1. 用pip install glumpy
2. 运行实例程序,报numpy不对，是因为nummpy版本低了，卸载nummpy后重新安装后解决:
pip uninstall numpy
pip install numpy

3.运行后报加载不到freetype的DLL
a.先下载freetype2的源码，然后用cmake编译，得到lib
b.发现需要加载dll,然后修改ft的工程属性，从静态库改成动态库，然后加上DLL_EXPORT宏.
c.将freetype.dll放在path环境变量能够找到的位置.

4.运行示例程序，又报没有backend.
1. 安装pyglfw,
2. 下载glfw3的dll,放在path环境变量能够找到的位置.

```javascript
const express = require('express')
const app = express()
 
app.get('/', function (req, res) {
  res.send('Hello World')
})
 
app.listen(3000)
```

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam qui voluptatem excepturi nemo similique atque sapiente aperiam, dolorum deleniti! Esse quam perferendis temporibus nemo at molestias necessitatibus tenetur cupiditate sapiente. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nihil et voluptatibus non labore officiis assumenda, distinctio perspiciatis blanditiis nesciunt rerum molestias impedit fugiat nulla qui libero minima quasi! Libero, iure.

```scss
body {
	font-family: 'Nunito Sans', sans-serif;
	line-height: 1.5em;
	margin: 0;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}
```
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam rerum, ratione impedit necessitatibus facere soluta odio repellat asperiores neque! Sunt iusto quia suscipit amet inventore eum, vel molestiae reiciendis alias.