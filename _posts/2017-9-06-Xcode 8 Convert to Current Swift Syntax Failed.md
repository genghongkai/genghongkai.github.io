---
layout: post
title:  "Xcode8 convert to current swift syntax failed"
date:   2017-09-06 23:06:02 -0700
categoryies: xcode
---

问题
当升级到 Xcode 8的时候，我们基本都需要升级 Swift 语法， 这个时候可能出现Convert to Current Swift Syntax Failed的问题 ：

大致的描述是说，在你的 XXXXTests 下找不到你的测试主机。


## Xcode 8 Convert to Current Swift Syntax Failed
```
1：选择你的工程项目
2：选择你的项目测试项，XXXXTests
3：选择 General .
4：看到Host Application 的选项是 Custom . 将其改为你的 工程 选项就好了.
5: 最后再重新转换语法 ，选择 Xcode 左上角 ，Edit -> Convert -> To Current Swift Syntax ...
6: 转换完编译一下就OK了。

```
