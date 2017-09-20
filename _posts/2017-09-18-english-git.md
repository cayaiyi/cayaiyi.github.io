---
layout: post
title: 英语学习- Git
date: 2017-09-18 00:00:00 +0300
tags: [English,Git] # add tag
---

### 单词

*  git 文件的版本控制工具,分布式工具 
*  status 状态  
*  add 添加
*  origin 源头,起源,最初的
*  master 主干 主要的
*  pull 拉取, 拉
*  push 推送 推动
*  stash 暂存
*  pop 弹出, 弹起来,跳起
*  all 所有的 
*  switch : 切换 ,开关


### git的组合命令

> git 所有的命令都要用 `git` 开头
 
 
* `git status` 查看当前的本地仓库状态 
*  `git pull origin master` 从远程库拉取最新的文件到本地库,防止 直接推送报错
*  `git add .` 添加 当前目录 所有的 未保存文件 到本地库
*  `git commit -m "注释内容"` 将刚才 添加到本地库的文件 这一系列行为 的 注释添加上
*  `git push origin master` 推送本地库的修改文件到远程库
* `git stash` 将本地的修改内容添加到 本地库的暂存区,主要用于 拉取远程文件时出现冲突 而不能拉取,但又不想将修改的内容添加到本地库的问题
* `git stash pop` 将本地库暂存区的文件 再释放出来,继续编辑
* `git branch -a` 列出本地所有的分支,a 就是 all
* `git checkout 分支名称` 根据分支名,切换分支 ,如果没有则 切换失败
* `git checkout -b 分支名称` 根据分支名称 切换分支, 如果没有就创建一个

### 参考链接

[Git 参考](https://rogerdudler.github.io/git-guide/index.zh.html)


