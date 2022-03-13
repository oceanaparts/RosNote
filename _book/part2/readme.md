# 2.功能包中的src文件夹下分析（不是与build平级的src):
（基于中科院教程https://www.bilibili.com/video/BV1mJ411R7Ni/）

src下放的是各种package（功能包），是编译的基本单元，每个package又可以被一同放在一个文件夹下，再放置于src下，每个package可以由各种语言共同构成，一般cpp放在source文件夹下，python放在scripts文件夹下；一个package可以包含多个可执行文件（节点），每个package下除了上述两个代码文件（scripts与source）以及include文件夹又包含着如下两文件（这两文件也是判断是不是package的方法）

  ![](https://s2.loli.net/2022/01/13/SV8dhckn4MNx5Zq.png)