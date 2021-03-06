---
title: MarkDown语法学习（一）
tags: MarkDown 学习日记
---

![](https://pan.qia.icu/images/2020/08/22/Qgqk7txaxN/i%E2%99%A5markdown.jpg)

学习MarkDown语法的标题使用、段落分段以及文字标记。  

<!--more-->

一.标题的使用
=============

1.使用`=`和`-`区分一二级标题
---------------------------

一级标题
========  
文字下方使用"="符号  

二级标题
-------  
文字下方使用"-"符号  


2.使用`#`的多少来划分标题
----------------------  
# 一级标题  
## 二级标题  
### 三级标题  
#### 四级标题  


二.段落分段
=============

1.使用两个空格键加回车符换行
--------------------------

```
123  
456
```
123  
456

2.或者使用空行的方式换行
-----------------------

```
789

10
```
789

10

3.使用空行加三个以上的星号`*`、减号`-`、底线`_`来建立一个分隔线
----------------------------

```
123

---
456

***
789

___
```
123

---
456

***
789

___

三.字体标记
=======

1.斜、粗、粗斜体使用`*`或`_`加在文字两侧
---------------------------  
```
  _文字lalala_      *文字lalala*
 __文字lalala__    **文字lalala**
___文字lalala___  ***文字lalala***
```
_文字lalala_  *文字lalala*  
__文字lalala__  **文字lalala**  
___文字lalala___  ***文字lalala***  

2.文字的两端加上两个波浪线 `~~` 添加删除线
-----------------------------  
`~~123~~` ~~123~~

3.下划线可以通过 HTML 的 `<u>` 标签来实现
------------------------------------  
`<u>1234<u>` <u>1234<u>

4.脚注通过`[^]:`完成
---------------------------------  

```
说我最帅了[^Me]  
创建脚注格式类似这样[^RUN]

[^Me]: 指Fanka.
[^RUN]: To be NO.1！！！
``` 
说我最帅了[^Me]  
创建脚注格式类似这样[^RUN]



[^Me]: 指Fanka.
[^RUN]: To be NO.1！！！

