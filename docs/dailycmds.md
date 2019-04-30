# 常用Linux命令

## 系统

|命令|功能|常用参数|
|--|-----------|----------|
|ls|列出文件及目录|-l -a -t -d -f|
|pwd|当前路径||
|find|查找|-name|
|which|查找给定命令的绝对路径||
|whereis|查找指令路径||
|mv|移动|-r|
|rm|删除|-r -f|
|cp|拷贝|-r|
|cat|查看文件||
|head|查看文件头| -n |
|tail|查看文件尾|-n |
|mkdir|创建文件夹|-p|
|df|查看磁盘占用| -h |
|du|查看文件和目录使用空间|-sh|
|scp|远程拷贝|-r|
|wc|计算数字|-l|
|history|查看历史命令||
|grep|文本搜索工具|-v -n -e等，[参考链接](http://man.linuxde.net/grep)|

注意Linux下**管道**的概念。

## VIM

1. 光标移动
   1. h,j,k,l,w,e,W,E,o,O
   2. $,^,gg,G
2. 编辑查找替换
   1. #, *, %, n, N, /, s
   2. i,I,a,A,c,x,s,p,P
3. 保存退出
   1. w,q
   2. saveas
4. 窗口
   1. vs, sp