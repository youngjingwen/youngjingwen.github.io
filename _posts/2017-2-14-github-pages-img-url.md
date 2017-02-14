---
layout: post
title: github pages md文档中图片链接失效
---

## 症状

---  
我的Github pages项目中 md文档中图片路径为`![](../img/file-system.png)`，访问`username.github.io`却发生图片链接失效的问题。

## 解决方法

把md文档中图片路径改为以链接的形式插入`![](https://youngjingwen.github.io/img/file-system.png)`

利用github存储图片，在markdown引用图片链接地址

#### 具体步骤：

 1.将markdown需要的图片放到git仓库中，发布到Github上
 2.访问Github仓库，找到图片
 3.右键点击图片，在新标签页中打开图片
 4.拷贝链接地址，在markdown中引用图片
