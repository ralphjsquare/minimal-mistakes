---
layout: post
title: Command Line
---
# Command Line
`brew install fortune`

`fortune`

Here's what I got,

>When the sun shineth, make hay.
>		-- _John Heywood_

While I am scrolling down _Az_ 's material about command line, some points seems quite abstract. I just cannot imagine how the command line `cat` will do for exploring the designated file, even though the output for the `cat` is not so pleasant to understand(mixed with binary stuff). The same goes with `touch` command, but it feels like a midas hand doing some magics. Not everything is in the comfort zone easily to pick up.

However, the second half pleases me so well. `Fortune` as the start of the article, is one of my favorite. Command `rig` can provide some fake identity(without SSN) for easy registry for some websites. Command `toilet` enables me to show off with amazing ASCII word. Other recommended by _Azeril_ , like `cmtrix` , `telnet towel.blinkenlights.nl`, and `sl` are quite entertaining.

## Basics
```
$ pwd ## Print Working Directory

$ cd ## Change Directory

$ cd - ##返回原先使用的一个目录

$ cd .. ##返回上一级目录

$ cd ~ ##返回用户主目录
```

####相对路径和绝对路径
```
$ cd .. ##工作目录的父目录

$ cd ~/Documents/Writings/2015 ##在任意目录下跳转

$ cd Writings/2015 ##在Documents的下跳转
```

####查看>列表
```
$ ls ##列表展示目录内容

$ ls /directory_path ## 制定目录列出内容

$ ls -a ## 列出包括隐藏文件在内的全部文件

$ ls -f ## 直接列出结果，不排序
```
####查看>属性及内容
```
$ file ##  确定文件类型

$ cat ##  显示文档全部内容

$ less ## 浏览文件内容， 退出时用q
```
####创建>文件夹
```
$ mkdir ## Make Directory 新建目录

$ rmdir ## 删除空目录
```
####创建>文件
```
$ touch file_name

$ >file_name

$ echo “words” > file_name
```
####复制
```
$ cp file_name directory_path

$ cp -l $$若目标文件已存在，覆盖前先询问

$ cp -a ## 连同文件特性一起复制

$ cp -r ## 递归持续复制， 复制目录
```
####移动
```
$ mv file_name directory_path

$ mv file_name .file_name ## 隐藏文件

$ mv -v ## 执行时反馈信息
```
####删除
```
$ rm -r directory_path ## -r(Recursive) 参数， 山楚墓路线所有内容

$ rm -rf directory_path ## -r 递归地删除目录和其中的内容 ； -f 强制删除而不输出确认信息

$ rm -rf / ## 删除整个系统的文件... 删除命令 / 代表根目录 -r 代表递归删除子目录及内容 -f 代表强制

$ rm -i file_name ## 删除前确认, i(interactive 交互性)参数
```
-

## Others

For me, the customized command `alias short_line＝’command_line’` , I do not quite figure out what I would do about it. Hope it will be there soon.

The last order,

>" Do not execute the command line that you do not know what it is! "


Archived.