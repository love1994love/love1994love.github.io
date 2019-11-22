---
layout: post
title:  "Git Desktop教程"
date:   2019-11-22 14:30:13
categories: software
tags: software default
comments: 1
---
> 本文介绍了GitHub Desktop更换账号后，如何将本地文件推送到登陆账号的仓库中。

#### 切换登陆账号

<img src="https://i.loli.net/2019/11/22/U13iNgJOnKmotTr.png"/>

更换完账号后，切换推送到git的仓库

<img src="https://i.loli.net/2019/11/22/PG2RJweyTSLzEjr.png"/>

#### 配置 Who you are

```git
git config --global user.name " user.name"
git config --global user.email " user.email"
```

**注意git config命令的–global参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址**

<img src="https://i.loli.net/2019/11/22/DVUcQjkIgFEYaHn.png"/>

更换完git仓库后，就可以推送到远程仓库了！