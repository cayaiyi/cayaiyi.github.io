---
layout: post
title: 英语学习- Jekyll
date: 2017-09-18 21:43:00 +0300
tags: [English,Jekyll] # add tag
---

### 单词

* ruby : 编程语言
* gem : 用ruby写的工具包
* jekyll : 一个用于生成静态网站的工具,gem的一个工具,使用gem安装
* serve : 服务器
* build : 构建
* control : 控制, 电脑的按键
* command : 命令,电脑按键
*  

### jekyll 组合命令

* jekyll serve : 启动jekyll 服务,生成本地预览的web网站
* control + c : 停止命令,比如开启了 jekyll服务,需要关闭的时候用
* jekyll build : 部署md文件,生成页面


### jekyill 新建md,生成页面

* 新建md文件,一般我使用MWeb软件,在`_posts`目录下面 新建以`md`结尾的文件
* `md`文件的标题有严格的命名规范如:`2017-xx-xx-xxxx.md` ,年月日-标题名称.md的格式
* 添加 头部的layout节点 ,注意腰写在文章的最上面,且不要空格

```
---
layout: post
title: 自定义标题
date: 自定义年月日,后面的不要改 00:00:00 +0300 
description: 自定义描述信息
img: i-rest.jpg # 可选,添加文章的预览图片名词,在`_posts的同级目录assets下面`
tags: [English] # 添加文章的标签,比如写的单词,就添加 English 标签
---

```

* 后面的就是文章的正文,基本就是markdown语法.



