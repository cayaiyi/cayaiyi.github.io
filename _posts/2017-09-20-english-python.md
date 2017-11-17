---
layout: post
title: 英语学习- python
date: 2017-09-19 14:10:00 +0300 
tags: [English,Python] 
---

### 单词

* **python**: 解释型,面向对象的脚本语言,它的特点是优雅,明确,简单,python适合开发web网站和各种网络服务,系统工具和脚本,另外python又是一种胶水语言可以把其他语言组合包装方便使用
* **raw** : 粗糙的,原始的
* **list**:有序的集合列表 
* **indexError**:表示索引超出范围
* **oppend**:附加
* **insert**:插入
* **pop**:删除
* **tuple**:元组,有序的列表
* **if**:如果
* **else**:否则
* **elif**:或者如果
* **for**:循环数组
* **while**:循环判断
* **break**:退出当前循环
* **continue**:跳过继续循环
* **dict**:用于关联查找
* **get**:得到


### 组合命令

* `python test.py` : test是文件名称,.py是python文件的后缀 , python 指定 脚本的执行语言是 python. 比如 linux的bash脚本,可以用 `sh test.sh`
* `raw` python中使用raw,主要是为了更方便的区分 正则表达式这一类有特殊符号含义的语法. raw字符串 里面的特殊符号不需要进行转义. 

### 语法

* `utf-8`:中文编码使用#-*- coding= utf-8 -*-
* '#': 使用#表示注释一整行代码
* `print`:输出指定的文字,输出文字print 'hello';,输出数字print 1;
* `r`:表示一个raw字符串,前缀加r,表示这串字符串不会被转换.
* `and`两个布尔值位true,结果为true,否则结果为false
* `or`一个布尔值为true,结果为true,否则为flase
* `not`把true变为flase,或者把flase变为true
* Python把0、空字符串''和None看成 False，其他数值和非空字符串都看成 True例如 a='' print "hello" a or 'python',结果hello python
* `list`:使用['xxx',1,'xxx']表示集合
* 索引从0开始,最后一个元素用-1表示
* `append()`:把新元素追加到末尾
* `insert()`:在集合中插入新元素,insert(0,'a')
* `pop()`:删除集合最后一个元素,如果括号中加索引,删除索引并打印出删除的该索引
* 替换集合中的元素语法是:变量名[索引]=替换的内容,如L=[1,2,3]  L[-1]=4
* `tuple`:不同于list的是不能替换,添加删除索引.但访问元素是一样的用中括号表示
* `单元素tuple`:括号中必须带逗号,否则打印的结果是一个整数,或者是一个字符串,元组表示方式为t=(1,)
* `tuple的指向不变`,但指向一个集合,这个集合可以替换或者删除和添加
* `if`语句语法:if 表单式 : 例如if are>=18:
* `else`:判断true和flase,else后面加冒号:
* `elif`:或者如果,用于多个判断 
* `for`:循环集合或者元组中的每个元素,语法 for 变量名 in 集合(元组列表名)打印for定义的变量名,得到列表中的元素
* `while`:判断循环是否结束,不能迭代集合和元组的每个元素 while 表达式 :
* `dict`:集合语法{'key':值}
* len():函数计算集合的大小
* get():dict提供的方法在键不存在的时候返回none
* 











