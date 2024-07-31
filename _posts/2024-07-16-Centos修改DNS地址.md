---
layout: post
title: Centos修改DNS地址
date: 2024-07-16
description: 修改DNS
tags: dns
---

# Centos修改DNS地址

## 修改DNS地址

```shell
vim /etc/resolv.conf

# 新增内容
nameserver 223.5.5.5 # 阿里云公共dns
nameserver 8.8.8.8 # Google公共dns
```
