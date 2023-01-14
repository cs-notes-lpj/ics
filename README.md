
**记得在课程结束后，回过头再来看** [这些曾经一知半解的问题](https://nju-projectn.github.io/ics-pa-gitbook/ics2021/why.html#%E4%B8%80%E7%9F%A5%E5%8D%8A%E8%A7%A3) **是否得到解决** ？

[课程官网](http://jyywiki.cn/ICS/2021/)、[PA/programming-assignment](https://nju-projectn.github.io/ics-pa-gitbook/ics2021/)

### 必看

- [crashCourse|计算机入门课](https://www.youtube.com/watch?v=tpIctyqH29Q)

- [C/C++ 语法基础](https://liupj.top/2021/08/11/c-toturial/)

### 选看

- 计算机系统基础（理论课）by 袁春风（NJU）

    - [上](https://www.icourse163.org/course/NJU-1001625001)、[中](https://www.icourse163.org/course/NJU-1001964032)、[下](https://www.icourse163.org/course/NJU-1002532004)

    - [又](https://www.icourse163.org/course/NJU-1449521162)、[还](https://www.icourse163.org/course/NJU-1464941173)

- C 语言 by 翁恺（ZJU）on [MOOC](https://www.icourse163.org/)

### 背景知识

什么是模拟器 ？

支付宝是一个程序，它的目标在于：用软件模拟出 ATM 机的功能（eg：存款、取款、转帐、...）

<img src="https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20220405190312821.png" width=400 />

同理，模拟器也是一个程序，它的目标在于：用软件模拟计算机硬件的功能进而支持在其上层运行其它程序

知名软件 [virtualbox](https://www.virtualbox.org/) 和 [vmware](https://www.vmware.com/) 均是能够模拟 pc 主机的软件，我们可以在模拟出的 pc 主机上运行操作系统

再比如 [NES Emulator](https://www.emulator-zone.com/doc.php/nes/)，这是一款可以模拟[红白机](https://baike.baidu.com/item/%E7%BA%A2%E7%99%BD%E6%9C%BA/4443886)的软件，我们可以在模拟出的红白机上运行各种[经典 NES 游戏](https://github.com/Brannua/nes-games)，比如魂斗罗、超级马里奥、...

### 本课程的终极目标

写一个简化了但功能完备的模拟器 NEMU（NJU EMUlator）

进而你就能理解「一个程序在被一步步地（预处理、编译、汇编、链接、执行、完成）的整个过程中，计算机究竟都做了什么」

让计算机执行程序的过程，在我的眼中不再是黑盒

![image-20220510122321626](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-picgo/image-20220510122321626.png)

### 选定的指令集

riscv32(64)

因为该指令集经典，且实现难度较小 :)

