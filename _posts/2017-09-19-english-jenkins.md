---
layout: post
title: 英语学习- Jenkins
date: 2017-09-18 00:00:00 +0300 
tags: [English,Jenkins] # add tag
---



### 单词

* jenkins : 持续化集成工具,可以为JAVA,iOS,安卓项目做自动化的集成,比如自动化源代码管理,编译,打包,部署,测试;以及相配套的邮件通知,文件上传下载等
* homebrew : Mac环境下的包管理工具,可以下载一些常用的工具,如Git,SVN,openssl,cocoapods,ruby,jenkins等等
* brew : homebrew 的简称
* install : 安装
* uninstall : 卸载
* 


### 组合命令

* brew list 查看已经安装的工具包,比如查看是否安装了 jenkins
* brew uninstall : 卸载 包工具
* brew install   : 安装 包工具
* java -jar jenkins.war --httpPort=8081: 直接用war包安装,指定端口是8081,如果冲突报错,就换一个端口
* initialAdminPassword : 初始化密码


### 报错说明 

* Address already in use : 端口被占用了,所以不能用默认的端口`8080`
* `Jenkins home directory: /Users/manajay/.jenkins found at: $user.home/.jenkins` , jenkins的war运行后生存的目录


### Mac下安装

* 官网下载 war包
* 切换到 war的下载目录
* 执行 `java -jar jenkins.war --httpPort=8081`
* 浏览器打开 `localhost:8081`  ,如果失败,则用具体的本地**IP**地址 : 比如 `192.168.1.102` 

* 自己试验的时候 要先将 本地运行的jenkins停掉


### Mac 下jenkins运行环境

```
// war包运行的地址
Running from: /usr/local/Cellar/jenkins/2.61/libexec/jenkins.war
// web项目运行的工作根目录,由war包运行生成
webroot: $user.home/.jenkins
```

