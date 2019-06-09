# Linux 是什么

## 操作系统

内核 + 系统调用

## 历史

### Unix

1973年贝尔实验室Thompson等人以C语言版本编写出正式版本的Unix。

后来广泛使用后，AT&T在79年收回版权，同时提到了“不可对学生提供源码”，引起多个商业纠纷。

### Minix

1984年，谭宁邦教授为避免版权纠纷，同时为了给学生上课，自己写了一个类似Unix的操作系统Minix。

谭宁邦教授始终认为Minix主要应用在教育上，以及学术很忙，所以虽然Minix很受欢迎，但是发展缓慢。

### GNU项目

1984年，Richard Mathew Stallman发起GNU项目。GNU(GNU's Not UNIX)目标是创建一个自由、开发的UNIX操作系统。

但是一开始无法进行（复杂的操作系统一个人无法完成等），GNU项目开始推出免费的的可以在Unix上运行的工具，于是伟大的Emacs, GNU C(GCC), GNU C Library(GLIBC) Bash shell等相继出来。

#### GNU GPL

自由软件版权的版权。为了避免自己的开发出来的Open Source自由软件被商用，Stallman给GNU的软件加上GPL版权声明。

#### Free的真谛

GPL(GNU General Public License)中强调**Free**:

1. 取得软件和源码。
2. 复制
3. 修改
4. 再发行
5. 回馈
6. 修改授权：不能取消GPL授权。
7. 单纯销售：不能单纯销售自由软件。

### Linux 0.02

Linus Torvalds在386上安装Minix并探索，Torvalds使用GNU的bash工作环境和gcc编译程序等自由软件发布Linux 0.02。

### Linux的开发

Torvalds将Linux发布在Ftp上，由单人维护到广大黑客志愿者加入共同完善Linux内核。

1994年Linux 1.0正式版发布。

1996年Linux 2.0正式版发布。企鹅作为吉祥物。

## Linux 内核

内核版本标号：
> 2.6.18-92.e15
主版本.次版本.释放版本-修改版本

1. 主次版本为奇数：开发中版本（development）
2. 主次版本为偶数：稳定版本（stable）

## Linux distrubitions(Linux发行版)

Linux其实就是一个操作系统最底层的内核及其提供的内核工具。

为了让用户接触Linux，商业公司将Linux Kernel与可运行的软件集成，加上工具程序，（Kernel + Softwares + Tools）称之为Linux distribution。

1. Red Hat
2. Fedora
3. Ubuntu
4. CentOS
5. Debian
6. ……

## Linux 的特色

1. 自由与开发的使用学习环境
2. 配备需求低廉
3. 内核功能强大稳定
4. 独立作业


## Linux的优缺点

优点：

1. 稳定的系统
2. 免费或者少许费用
3. 安全性、漏洞的快速修补
4. 多任务、多用户
5. 用户与用户组的规划
6. 相对比较不耗资源的系统
7. 适合需要小内核程序的嵌入式系统
8. 整合度佳且多样的图形用户界面

缺点：

1. 没有特定的支持厂商
2. 游戏的支持不足
3. 专业软件的支持不足
