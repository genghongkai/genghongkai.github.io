---
layout: post
title:  "2017-9-7-UITableView、UICollectionView、UIScrollView顶部预留空白问题"
date:   2017-09-07 24:06:02 -0700
categoryies: UI
---


### 处理方法：

self.automaticallyAdjustsScrollViewInsets = NO;
```
原因：UIViewController下如果只有一个UIScollView或者其子类（UITableView,UICollectionView），那么会自动留出空白，让scollview滚动经过各种bar下面时能隐约看到内容。但是每个UIViewController只能有唯一一个UIScollView或者其子类，如果超过一个，需要将此属性设置为NO,自己去控制留白以及坐标问题。
```
