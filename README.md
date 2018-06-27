# hut-sec 暑期养成记 

## Target
这学期大家学习了不少网络安全基础技能，以及一些ctf的相关知识  
下学期开学之后会有一段时间高强度的ctf国际赛，请大家做好准备  
  
暑期的任务主要查漏补缺，以及完成一些前置技能的修炼，顺利的度过入门期  
一下是一些小任务，Web和Bin的任务各不相同，根据自己方向选择  
许多内容是已经掌握的就可以跳过，根据自身情况进行查漏补缺,Common类型是都要完成的  

## Common
- 搭建一个自己的博客（推荐hexo）

## Web
- 掌握基础的漏洞类型 ：了解漏洞原理（sql注入、xss、csrf、文件上传）
- 学习python的使用 ： 基础语法，以及一些常用库（requests、re）
- 学习sql语句：掌握对数据的增（insert）删(delete)改(update)查(select),以及表的创建（create）
- 了解http协议（推荐《图解http》）
- 学习linux基础操作：  
&nbsp;&nbsp;命令行中文件的移动、编辑、删除、修改权限、端口查看、进程查看    
&nbsp;&nbsp;自己搭建一个linux下的websever(apache/nignx + php + mysql)  
- 了解实际渗透（视频资源链接：https://pan.baidu.com/s/1Vg38Fehuc27dIiKvytTXXg 密码：0em8） 
- **前面学习完后有额外精力**的，学习MVC框架，尝试自己用php写一个小型mvc的web框架


## Bin
**前置技能**：
  - 掌握汇编基础：王爽汇编、逆向工程核心原理（可选）

### Pwn
  - 基础的调试、入门首选 [LiveOverFlow](http://liveoverflow.com/binary_hacking/) 或者 [bilibili搬运](https://www.bilibili.com/video/av18860370/) （原版可以自动翻译）
  - 完成 [exploit-exercises protostar](https://exploit-exercises.com/protostar/) 优先独立完成，部分练习用时太长可以选择看writeup
  - 学习 stack overflow：明白原理，完成例题 [基本ROP](htt)) 有限是ps://ctf-wiki.github.io/ctf-wiki/pwn/stackoverflow/basic_rop/)
  - 继续完成 ctf-wiki 栈溢出部分
  前面都完成的开始进阶
  - [how2heap](https://github.com/shellphish/how2heap)
  - [pwnable.tw](https://pwnable.tw/) [pwnable.kr](http://pwnable.kr/play.php)
  - ctftime ...

### Reverse
  - 学习程序调试技能：逆向工程核心原理
  - 可选学习教程 [reversingwithlena-tutroial](https://tuts4you.com/e107_plugins/download/download.php?action=view&id=2876) 一篇 简单的 crackme [An Intro to x86_64 Reverse Engineering](https://leotindall.com/tutorial/an-intro-to-x86_64-reverse-engineering/)
  之后就是不停的练习 [crackmes](https://github.com/crackmes/crackmes) 以及内功修炼：程序开发、操作系统、编译原理 ...
  
### 参考资料
  - [Linux (x86) Exploit Development Series](https://sploitfun.wordpress.com/2015/06/26/linux-x86-exploit-development-tutorial-series/)
  - [Linux (x86) Exploit 开发系列教程](https://bbs.pediy.com/thread-217390.htm)
  - windows平台： [Exploit writing tutorial part 1 : Stack Based Overflows](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/) [Part 1: Introduction to Exploit Development](https://www.fuzzysecurity.com/tutorials/expDev/1.html)
  - [exploit入门级](http://martin.uy/blog/projects/reverse-engineering/)
  - [一步一步学ROP x86](http://www.vuln.cn/6645)
  - 论坛：看雪、吾爱、tuts4you

# Reference
- [Web-Security-Learning](https://github.com/CHYbeta/Web-Security-Learning) （较好的web安全相关学习资源）
- [CTF-All-In-One](https://github.com/firmianay/CTF-All-In-One) （一本 CTF 领域的大杂烩指南）
- [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) （非常全面的黑客技术清单）
- [CTF-Wiki](https://ctf-wiki.github.io/ctf-wiki/) （CTF的入门简介）
