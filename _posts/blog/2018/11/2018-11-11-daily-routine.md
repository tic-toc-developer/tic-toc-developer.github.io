---
layout: post
title: Driver Complete
categories: Blog
description: 
keywords: GitHub
---

The codes in repo [Arduino-JY901-Serial](https://github.com/paul-tian/Arduino-JY901-Serial) is now with full abilities to receive data from JY901, but some can't be tested cause these data are not send by default and need to co-op with the (Host -> JY901) functions.  

Today I also figured out that in most of the time, endianness won't affect the bit shifting, cause the bit shift proceed in the register of CPU, not in memory. I believe that endianness is an interesting key to peek into the history of the computer science.

[homepage](/)
