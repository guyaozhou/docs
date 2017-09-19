---
title: Linux 常见问题解决方法
date: 2017-07-26 12:00:00
updated:
comments: true
tags:
- Linux
categories:
- Linux
---

# sudo

## 找不到命令

```bash
$ sudo vi /etc/sudoers

Defaults  secure_path=...
# 在后边加上PATH
```

<!--more-->

## 脚本输入密码

```bash
echo "password" | sudo -S cmd
```

# 相关链接

* http://blog.csdn.net/wangbole/article/details/17579463