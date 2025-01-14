---
layout: linux编译安装python
title: Linux编译安装Python
date: 2024-11-19 18:21:06
categories:
- python
tags:
- python
- build
---

[下载Python源代码](https://www.Python.org/ftp)

# 依赖
- [C11](https://en.cppreference.com/w/c/11) 编译器。 [可选的 C11 特性](https://en.wikipedia.org/wiki/C11_(C_standard_revision)#Optional_features) 不是必须的。
    
- 对 [IEEE 754](https://en.wikipedia.org/wiki/IEEE_754) 浮点数和 [浮点 Not-a-Number (NaN)](https://en.wikipedia.org/wiki/NaN#Floating_point) 的支持。
    
- 对线程的支持。
    
- 用于 [`ssl`](https://docs.python.org/zh-cn/3.12/library/ssl.html#module-ssl "ssl: TLS/SSL wrapper for socket objects") 和 [`hashlib`](https://docs.python.org/zh-cn/3.12/library/hashlib.html#module-hashlib "hashlib: Secure hash and message digest algorithms.") 模块的 OpenSSL 1.1.1 或更新版本。
    
- 在 Windows 上，需要 Microsoft Visual Studio 2017 或更新版本。

进入仓库文件夹

```
./configure
```

可指定: --prefix=

设置安装目录