# 计算机类学习资料

- [1. 资源合辑](#1-资源合辑)
- [2. 计算机科学基础](#2-计算机科学基础)
- [3. 编程语言](#3-编程语言)
  - [3.1. Python](#31-python)
  - [3.2. R](#32-r)
- [4. 算法](#4-算法)
- [5. 杂七杂八](#5-杂七杂八)

本人总结的部分计算机类学习资料（中/英文），其实很多我并没有看过或者看完 😅，请依个人口味酌量食用。

## 1. 资源合辑

- [免费的编程中文书籍索引](https://github.com/justjavac/free-programming-books-zh_CN)  
  特点：**免费**（开源）的**书籍**。但其实很多优秀的书籍并不是免费的，可以前往一些网站搜索：

  - Library Genesis: ~~一个特殊的网站.~~ [站点 1](http://libgen.li/), [站点 2](http://libgen.gs/), [站点 3](http://libgen.lc/), [站点 4](http://genesis.lib/).

- [自学计算机科学](https://github.com/keithnull/TeachYourselfCS-CN/blob/master/TeachYourselfCS-CN.md)  
  [TeachYourselfCS](https://teachyourselfcs.com/)的中文翻译。用最快的时间学最好的课程，真正的计算机科学！

以下主要根据个人学习经历补充（或者强调上面包含的）一些资料。

## 2. 计算机科学基础

- [计算机科学速成课](https://www.bilibili.com/video/BV1EW411u7th?p=1)  
  英文原版：[Crash Course Computer Science](https://www.youtube.com/watch?v=tpIctyqH29Q&list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo). 有趣的入门课，制作非常用心，自底向上，并且结合历史介绍了整个计算机科学的大部分内容。假如早一点看到该多好！
- [计算机组成原理 MOOC（电子科技大学）](https://www.xuetangx.com/course/UESTC0809003187)

## 3. 编程语言

### 3.1. Python

**基础：**

- [莫烦 Python 基础教程](https://mofanpy.com/tutorials/python-basic/)  
  讲解比较生动，非常适合入门，但相比于课程和书籍可能稍欠严谨。
- [免费的编程中文书籍索引：Python 部分](https://github.com/justjavac/free-programming-books-zh_CN#python)  
  资料挺多的，当年我是看着~~Python 之父~~廖雪峰的课入~~坑~~门的。
- [PythonShare](https://github.com/Yixiaohan/codeparkshare)
  面向零基础 Python 学习者的资料和学习指导。
- [Coursera 上的 Python 课程](https://www.coursera.org/search?query=python&)  
  这种课程就像本科的专业课（当然比起真实课程要简单一些），一般来说课程难度不高 (beginer)，如果加上了“数据分析”那就成了 (intermediate)🤣.
- [MIT Python 课程](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/)  
  当年看过这门课的[edX 版本](https://www.edx.org/course/introduction-to-computer-science-and-programming-7)，感觉对于没有学习过计算机的同学来说比较有用，顺带介绍了一点计算机基础知识。

- [斯坦福 CS41](https://stanfordpython.com/)  
  估计比 MIT 的稍微难一点点。

- [Python 官方教程](https://docs.python.org/zh-cn/3/tutorial/index.html)  
  相当于一本教科书了，很全面，但可能略显枯燥。

- [Python 标准库 API](https://docs.python.org/zh-cn/3/library/index.html)  
  详细描述了库或者函数的使用方法。不应该用来读，而应该当作**字典**来查。

<u>心得</u>：对于入门的同学来说，其实不需要纠结该上哪门课，基本学会学到对象、使用一些常用库这些就够了（日常使用并不需要太复杂的高级技术）。所以其实随便挑个对胃口的，快速学一遍就好。**关键点是多写代码，而不是多上课！**

**中级**

- [Practical Python](https://dabeaz-course.github.io/practical-python/)  
  知识点并没有比基础难很多，但是个人感觉更适合学完基础用这个来复习。
- [Python 进阶（中文版）](https://github.com/eastlakeside/interpy-zh)  
  英文版叫[_Intermediate Python_](https://book.pythontips.com/en/latest/index.html)，作者也称之为*Python Tips*。简洁明了，同时涉及到一些更高级的特性，比如装饰器。
- [Python 黑魔法手册](http://magic.iswbm.com/zh/latest/index.html)
  也是类似于*Python 进阶*的“小册子”，但是内容更加丰富。
- [流畅的 Python（中文版）](http://libgen.li/item/index.php?md5=A5DA1D0215997469860AEB16A4A4B146)  
  高屋建瓴，妙不可言。
- [Pro Python 3](https://www.amazon.com/Pro-Python-Features-Professional-Development/dp/1484243846)  
  推荐自《Python 进阶》，还没来得及看。
- [Intermediate Python](https://leanpub.com/intermediatepython)  
  推荐自《Python 进阶》的同名书籍，同样还没来得及看。
- [Composing Python](https://composingprograms.com/)  
  新版[伯克利 CS61a](https://cs61a.org/)，主要内容：

  - methods for abstraction
  - programming paradigms
  - techniques for managing the complexity of large programs.

  是一门计算机入门的专业课程。[旧版的 CS61a](https://www.bilibili.com/video/av40460492/)使用 Scheme 语言，教材为[《计算机程序的构造和解释》](https://book.douban.com/subject/1148282/)(Structure and Interpretation of Computer Programs, SICP)。该课程和教材都是经典中的经典。当然对于学习 Python 的同学来说，新版更容易上手。

### 3.2. R

基础：

- [R Programing for Data Science](https://www.cs.upc.edu/~robert/teaching/estadistica/rprogramming.pdf)  
  Coursera 上有简化版的课程[R Programming](https://www.coursera.org/learn/r-programming)，入门还不错。对于有编程基础的同学来说有点啰嗦，建议直接看[课件](http://ocw.jhsph.edu/index.cfm/go/viewCourse/course/rprog/coursePage/lectureNotes/)。

- The Art of R Programming  
  很流畅，推荐一读。

## 4. 算法

目前正在看算法，~~因为脑子转的慢，看的非常慢~~。

- [Fucking Algorithm](https://github.com/labuladong/fucking-algorithm)  
  大神之作！刷题找工作必备。
- 《算法 4》  
  入门必读！想了解算法的原理，可以忽略 Java 编程部分（或者看个大概即可）。
- [Coursera 斯坦福算法专项课程](https://www.coursera.org/specializations/algorithms)  
  老师讲的真的很棒，简明扼要。
- [斯坦福 CS161](https://web.stanford.edu/class/cs161/lectures.html)  
  刚刚找到的，还没看。

## 5. 杂七杂八

- 我写的一个[小抄集合](https://github.com/dull-bird/awesome-cheat-sheets)。
- [计算机教育中缺失的一课](https://missing-semester-cn.github.io/)  
  The Missing Semester of Your CS Education 中文版。
