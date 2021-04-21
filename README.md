# 面试任务 - git 仓库

## 基本要求

使用 react

不可以使用class组件，只能使用函数组件

使用 hooks 方式

不能直接更改 state ，只能使用 setState 更改 state

## 页面显示

* <name> - 🌟 <stars> - 🍴 <forks>
* react - 🌟 69012 - 🍴 12581
* reselect - 🌟 7291 - 🍴 214
* redux - 🌟 31705 - 🍴 6581
* recompose - 🌟 5671 - 🍴 342

[上一页按钮][下一页按钮][当前页数/总页数]


## 数据接口

> 数据接口：https://api.github.com/search/repositories?q=react&page=2 <br>
> 功能：获取 repositories 数据
> 请求方式：GET

## 任务描述

1. 使用数据接口获取数据，按 "页面显示" 小节那样显示出来
2. 已经下载过的页面，不需要再下载，可以直接从缓存中获得数据
3. 缓存只能缓存 5 个页面（可以在代码中配置这个数量）
