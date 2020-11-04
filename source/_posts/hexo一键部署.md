---
title: hexo一键部署
author: beagle的小伙伴
date: 2020-11-03
tags: hexo标签
categories: hexo目录
---

> 本文记录一下小红帽和beagle的小生活
未尽事宜，请多多指教
<!-- more -->
<!-- toc -->

## hexo写博客的流程如下：

### 文件创建

  ```bash
  $ hexo new post_name
  ```

  通过上述命令，在source/_post目录下生成一个待写的post_name.md文档


### 编译文件

  ```bash
  $ hexo generate
  ```

  将post_name.md编译生成对应的HTML文件


### 本地预览

  ```bash
  $ hexo s
  ```

  进行本地效果预览

### 推送到远程

  ```bash
  $ hexo deploy
  ```

  发布到远程仓库的master分支上，个人站点就可以看到最新文章



## 附：安装hexo

```bash
安装node.js
node -v
npm -v
npm i hexo-cli -g
hexo -v
```

