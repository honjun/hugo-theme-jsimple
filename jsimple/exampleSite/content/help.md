---
title: "关于此博客搭建"
date: 2019-04-20T13:29:27+08:00
type: "help"
author: hojun
avatar: 'https://cdn.jsdelivr.net/gh/honjun/ImageHosting/sina/006bYVyvgy1ftand2qurdj303c03cdfv.jpg'
authorLink: /about/hojun.html
authorDesc: 一个好奇的人
authorAbout:
keywords: 博客 blog hexo github
description: 使用hexo搭建github博客
photos:
 - https://wx4.sinaimg.cn/large/006bYVyvgy1fljtskjz95j304g04g749.jpg
---
## **第一步 环境**

参照简书这篇文章 [20分钟教你使用hexo搭建github博客](http://www.jianshu.com/p/e99ed60390a8)
咳咳，对于小白好像挺烦的样子。需要git账号，本地电脑安装git,node.js,hexo等等。有机会再补上windows教程吧。不过和mac也差不了。

## **第二步 blog模板**

在HEXO官网Themes可以自己挑选喜欢的模板。该博客使用的模板为[JSimple](https://github.com/tangkunyin/hexo-theme-jsimple)
关于该模板使用注意
### **1.建议使用作者博客备份，在上面稍加修改**
地址：https://github.com/shuoit/blog
### **2.注意模板依赖**
![image.png](https://www.tuchuang001.com/images/2017/06/25/image.png)

比如JSimple的依赖为
```
"dependencies": {
    "hexo": "^3.2.2",
    "hexo-git-backup": "^0.1.2",
    "hexo-renderer-ejs": "^0.2.0",
    "hexo-renderer-marked": "^0.2.11",
    "hexo-renderer-stylus": "^0.3.1",
    "hexo-server": "^0.2.0",
    "hexo-deployer-git": "0.2.0",
    "hexo-generator-archive": "^0.1.4",
    "hexo-generator-category": "^0.1.3",
    "hexo-generator-index": "^0.2.0",
    "hexo-generator-tag": "^0.2.0",
    "hexo-generator-json-content": "^2.2.0"
}
```

修改依赖后记得cmd到博客目录下
```
npm install
```
