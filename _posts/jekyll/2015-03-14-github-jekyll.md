---
layout: detail_tmp
title: Jekyll 安装教程
intro: 1.下载Rubyisntallersdownloads 一路下一步。
categories: Jekyll
keyword: 协作开发，github 教程，jekyll教程
author: H君
show_type: image
show_intro: /res/img/page/jekyll/open-source.png
tags: [Jekyll]
---

# Jekyll 安装教程

`Jekyll` `GitHub`

--- 

## GitHub 与 Jekyll

![jekyll和github教程](../res/img/page/jekyll/open-source.png) 



1.下载Rubyisntallers[downloads](http://rubyinstaller.org/downloads/) 一路下一步。

2.下载`Devkit` 就在下载`Ruby`的下面。完成后解压。注意和Ruby版本一致。

3.用`cmd` cd 到 Devkit 目录，运行。
    
    ruby dk.rb init 

4.修改`config.yml` 根据示例，添加`Ruby` 和 `Devkit`的路径。

5.执行
    
    ruby dk.rb install

6.安装 Jekyll(后续，安装Jeykyll 问题汇总。)
    
    gem install jekyll

7.下载完成.我们可以cd 到从Github clone 下来的项目。

    jekyll serve


