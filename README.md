# hut-sec 

## 前言
目前比较主流的两个网络安全大方向，也是我们组主要的两个方向

 - Web安全
 - 二进制安全

简单的说 Web安全主要研究对象是运行的Web服务，偏向应用层。  
二进制安全会更底层，对基础要求比较高。  

可以自己通过搜索引擎了解一下这两个方向的相关知识。（信息搜集能力也是一个黑客的必要前提

考虑到大部分人之前可能没有了解过，会给一段考虑选择的时间。前期可以两个都学，然后选一个适合自己的方向深入学习。

**最迟**需要在**寒假结束前**给出明确的学习方向。

以下是目前两个方向的学习计划。

## Web
Web安全的基础是开发，需要知道网站是如何运作的，才能知道网站是如何被攻击的（know it then hack it

- **了解** 静态网页基础 html 、css 、 javascript
- **熟悉** 一门动态Web开发语言 —— PHP 
- **了解** 基础数据库使用 —— MySQL的增删改查

注意**了解**和**熟悉**的区别。

最终的目的需要自己实现一个小型留言板的网站。


## Bin
**前置技能**：

  - 掌握汇编基础：王爽汇编、逆向工程核心原理（可选）

### Pwn
  - 基础的调试、入门首选 [LiveOverFlow](http://liveoverflow.com/binary_hacking/) 或者 [bilibili搬运](https://www.bilibili.com/video/av18860370/) （原版可以自动翻译）
  - 完成 [exploit-exercises protostar](https://exploit-exercises.com/protostar/) 优先独立完成，部分练习用时太长可以选择看writeup
  - 学习 stack overflow：明白原理，完成例题 [基本ROP](https://ctf-wiki.github.io/ctf-wiki/pwn/stackoverflow/basic_rop/)
  - 继续完成 ctf-wiki 栈溢出部分

  前面都完成的开始进阶
  - [how2heap](https://github.com/shellphish/how2heap)
  - [pwnable.tw](https://pwnable.tw/)、[pwnable.kr](http://pwnable.kr/play.php)
  - CTFTime ...

### Reverse
  - 学习程序调试技能：逆向工程核心原理
  - 可选学习教程 [reversingwithlena-tutroial](https://tuts4you.com/e107_plugins/download/download.php?action=view&id=2876) 一篇 简单的 crackme [An Intro to x86_64 Reverse Engineering](https://leotindall.com/tutorial/an-intro-to-x86_64-reverse-engineering/)

  之后就是不停的练习 [crackmes](https://github.com/crackmes/crackmes) 以及内功修炼：程序开发、操作系统、编译原理 ...

### 参考资料
  - [Linux (x86) Exploit Development Series](https://sploitfun.wordpress.com/2015/06/26/linux-x86-exploit-development-tutorial-series/)
  - [Linux (x86) Exploit 开发系列教程](https://bbs.pediy.com/thread-217390.htm)
  - windows平台： [Exploit writing tutorial part 1 : Stack Based Overflows](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)、[Part 1: Introduction to Exploit Development](https://www.fuzzysecurity.com/tutorials/expDev/1.html)
  - [exploit入门级](http://martin.uy/blog/projects/reverse-engineering/)
  - [一步一步学ROP x86](http://www.vuln.cn/6645)
  - 论坛：看雪、吾爱、tuts4you

# Reference
- [Web-Security-Learning](https://github.com/CHYbeta/Web-Security-Learning) （较好的web安全相关学习资源）
- [CTF-All-In-One](https://github.com/firmianay/CTF-All-In-One) （一本 CTF 领域的大杂烩指南）
- [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) （非常全面的黑客技术清单）
- [CTF-Wiki](https://ctf-wiki.github.io/ctf-wiki/) （CTF的入门简介）
