---
title: 使用Hexo+github搭建个人博客
date: 2017-06-27 15:34:45
tags:
---

[Hexo](https://hexo.io/)!搭建本地博客[(doc)](https://hexo.io/docs/) 。
[github](https://github.com)发布博客[我的博客地址](https://scorpdi.github.io)

## Quick Start

### 安装hexo

``` bash
$ npm install -g hexo
```

### 新建文件夹进行初始化

``` bash
$ hexo init
```

### 创建新的文章

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### 运行本地服务器 访问[http://localhost:4000/](http://localhost:4000/)

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### 生成静态页面至public目录

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### 配置好github仓库等之后就可以使用下面命令，将.deploy目录部署到GitHub

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

## 配置Github

### 新建仓库

建立与你用户名对应的仓库，仓库名必须为【your_user_name.github.io】，固定写法

然后建立关联
在_config.yml文件中设置
``` bash
# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type: git
  repository: git@github.com:scorpdi/xxxxx.github.io.git
  branch: master
```

执行配置命令：
```
hexo deploy
```
访问[https://scorpdi.github.io/](https://scorpdi.github.io/)（我的github账号）
