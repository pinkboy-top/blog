---
title: 初认Python
date: 2016/7/28 15:46:26
layout: python
permalink: python.html
---
---
## 人生苦短我用python
---
<!--more-->
## Python简介
Python是一种广泛使用的解释型、高级编程、通用型编程语言，由吉多·范罗苏姆创造，第一版发布于1991年。Python是ABC语言的后继者，也可以视之为一种使用传统中缀表达式的LISP方言。Python的设计哲学强调代码的可读性和简洁的语法（尤其是使用空格缩进划分代码块，而非使用大括号或者关键词）。相比于C++或Java，Python让开发者能够用更少的代码表达想法。不管是小型还是大型程序，该语言都试图让程序的结构清晰明了。

与Scheme、Ruby、Perl、Tcl等动态类型编程语言一样，Python拥有动态类型系统和垃圾回收功能，能够自动管理内存使用，并且支持多种编程范式，包括面向对象、命令式、函数式和过程式编程。其本身拥有一个巨大而广泛的标准库。

Python 解释器本身几乎可以在所有的操作系统中运行。Python的其中一个解释器CPython是用C语言编写的、是一个由社区驱动的自由软件，目前由Python软件基金会管理。
## 快速上手
国际惯例首先从hello world开始
python的特点就是语法简单能够很快速的上手,实现hello world只需要使用python3的print()函数即可打印输出想要的内容
~~~
print("hello world")
~~~
---
## 安装python
---
> 首先去python官网下载对应系统版本的python安装包
> [python官网](https://www.python.org/)
> 这里以windows为例子去安装下载
> -
> **下载安装3.5版本**
> ![下载安装3.5版本](https://i.loli.net/2020/10/02/3PbltuiDS95wYQk.png)
> **把python添加到系统环境变量**
> ![20201002201022](https://i.loli.net/2020/10/02/ZQvAxTzkaupHWsf.png)
> **这些都安装**
> ![20201002201251](https://i.loli.net/2020/10/02/FCaO9R4xkWVj1G2.png)
> **安装完成后打开cmd看下是否成功**
> ![20201002201508](https://i.loli.net/2020/10/02/M7Oo1HdzaBnZxAI.png)
> **执行一下print函数**
> ![20201002201728](https://i.loli.net/2020/10/02/FayOqmjtbDgLHri.png)
> **到这里我们的python安装已经完成了**
---
## python基础
---

> **python包管理器pip的使用**
> pip3 install 你需要安装的库或者模块
> pip3 uninstall 需要卸载的模块或者包
> pip3 list 安装列表
> python的pip包管理器功能非常的强大类似Ubuntu系统的apt和centos的yum在安装和导入模块的时候非常有用务必掌握.

> **安装request编写一个获取百度首页的简单爬虫程序**
> ![20201002203140](https://i.loli.net/2020/10/02/ohaZBlN1EwArxRu.png)

> **编写代码**
> ~~~
> import requests # 导入requests模块
> s = requests.get(url="https://www.baidu.com") # 打开百度
> print(s.status_code) # 打印请求状态码
> print(s.text) # 打印获取到的网页源码
> ~~~

> **打开python自带的ide写入对应代码执行**
> ![20201002205216](https://i.loli.net/2020/10/02/ahTD3ktzOYZWgKr.png)