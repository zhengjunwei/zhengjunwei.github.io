---
layout: post
title:  "laravel"
date:   2015-10-07 15:57:54
categories: jekyll update
---
- 安装xampp(php版本要5.5以上)
- 安装composer
- php composer.phar global require "laravel/installer=~1.1"
- composer create-project laravel/laravel --prefer-dist
- 成功创建了一个laravel项目
- 开启php的open ssl扩展
- php artisan key:generate （要不然会报 encripter not found)
- 安装成功