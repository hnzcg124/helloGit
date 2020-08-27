# Git笔记

# 一.git指令

git：分布式版本管理工具

``` shell
git -version
git configl -l

#配置用户名 邮箱
git config --global user.name "tea.year"
git config --global user.email "china_zyb@qq.com"
```

## 二.仓库的概念

实际就是文件夹

Git管理的就是仓库中的内容。仓库中的每个文件的改动，都会被git追踪。

``` shell
git add xx
git add xx.java
git .

#提交文件
git commit -m "this is a file"
git commit -a -m "xxx" 自动住家，并提交
#查看文件状态
git status
再增加一个文件，再查看一下状态，会发现问题

#提交部分文件
git commit -m "add som files"
#删除文件
git rm hello.java 并git commit hell.java -m "xxx"即可
#帮助
git help commit 或git commit --help

```

## 三.日志

在IDEA下设置

![image-20200826090429485](E:\政通路\课堂笔记\S3\git\assets\image-20200826090429485.png)

使用自己的GitHub账户登录一下

![image-20200826090452923](E:\政通路\课堂笔记\S3\git\assets\image-20200826090452923.png)



# 二.IDEA和Git

