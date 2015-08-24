---
layout: post
title:  "iWatch debug 方式 "
date:   2015-08-24 16:21:13
---
#iWatch debug 方式 

###问题背景
初次进行iWatch开发时候会发现在iWatch app extension的代码打的断点不生效，NSLog也无法打出日志。

###解决办法
解决方法很简单，依照以下三步即可：
- 首先run 起来Apple Watch App在模拟器中。
- 在iphone 模拟器中启动 demo App。
- Xcode - Debug - Attach to Process 里找到host app 线程，Attach上。