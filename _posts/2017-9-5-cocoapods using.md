---
layout: post
title:  "cocoapods using"
date:   2017-09-05 23:06:02 -0700
categories: cocoapods
---
### 进入项目文件夹下，终端命令：

```
$ cd desktop/myproduct

$ vim Podfile

1.把下面内容复制到Podfile 文件中。

platform :ios, '8.0'

target 'myproduct' do   //在 myproduct 项目中执行
pod ‘AFNetworking’
end

2.按下 ESC键(结束编辑模式)-> shift+: -> wq

shift 键 + 冒号键 跳到文本结尾， wq 表示保存退出。    q 退出

$ pod install 

命令执行后如下：
Analyzing dependencies          //分析依赖
Downloading dependencies        //下载依赖
Installing AFNetworking (3.1.0) //安装 afnetworking (3.1.0)版本库
Generating Pods project         //生成 Pods project
Integrating client project      //整合 client project

```
