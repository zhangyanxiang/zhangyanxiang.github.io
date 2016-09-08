---
layout: wp
title: 理解vagrant
---
介绍：<br/>
一款用于快速创建及部署开发环境的工具，一个中间层技术，底层是VirtualBox、VMware等

特点：<br/>
1、便于团队开发环境管理<br/>
2、相同的Vagrantfile文件可以跨平台使用（Linux、unix、Mac OS、windows）

安装：<br/>
1、安装VirtualBox<br/>
  https://www.virtualbox.org/wiki/Downloads <br/>
2、安装Vagrant<br/>
 https://www.vagrantup.com/downloads.html<br/>
3、如果有现成的virtualfile文件则放到指定路径然后执行 vagrant up<br/>
例：文件在E:\va下  执行如下；<br/>
![vagrant up执行页面](http://i2.buimg.com/567571/1c98d42b7747b33f.jpg) <br/>
---markdown插入图片：访问http://yotuku.cn/ 上传图片，之后在markdown插图的地方输入格式![描述](图片链接)<br/>
 如果没有现成的文件则执行 vargant init 进行初始化---会生成一个virtualfile文件

