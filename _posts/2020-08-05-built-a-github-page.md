---
title: 使用github pages搭建个人博客
date:  2020-08-05 11:26:33 +0800
category: blog
tags: test
excerpt: 省去服务器搭建自己的博客网站。
---

偶然一次知道使用github repo可以存放静态网页代码，因此可以以此来搭建自己的博客。以前在服务器中搭过wordpress，但是一旦服务器挂了，博客文件也都没了。因此在github中搭建博客也不失为一个不错的解决方案。

github pages官方网站：https://pages.github.com/

官方推荐jeklly主题框架，因此在github中找到了这个主题：https://github.com/showzeng/Minimalism，感觉不错，因此把它clone下来上传到自己的github。

**1.准备步骤：新建一个repo，仓库名字为xxx.github.io，其中xxx为你github的username。**

**2.把想要的主题clone下来：**
示例代码：
```
git clone https://github.com/showzeng/Minimalism.git
```


**3.再把刚才自己新建的repo clone下来：**
```
git clone http://github.com/varenyzc/varenyzc.github.io.git
```

**4.接着把主题文件夹中除了.git文件夹全部复制到自己仓库所在的文件夹**

**5.在自己仓库文件夹中右键git bash here**
代码如下：
```
git add .
git commit -m "first commit"
git push -u origin master
```

至此完成博客的搭建。过点时间访问xxx.github.io就可以访问到你的博客啦！
