---
layout:     post
title:      typora如何不使用图床也能保存图片
subtitle:   typora防止插入的图片丢失
date:       2020-04-09
author:     Zengpeizhi
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - typora
    - markdown
    - 插入图片
---
# 利用github永久保存markdown插入的图片

最近开始了利用gitpage搭建自己的博客，然后开始了markdown的写作之路，发现其实markdown写作有两个难处，第一：**公式输入**，第二：**图片插入markdown后很容易丢失**

### 公式插入问题

这个问题还是比较好解决的，给大家推荐一个mathpix的软件，可以直接截图然后就识别成对应的公式latex。识别准确率很棒！！！强烈推荐！大致的使用效果如图：

![](https://github.com/Zengpeizhi/Zengpeizhi.github.io/blob/master/img/markdown1.png?raw=true)

**一个小tips**：最好使用学校邮箱注册，可以免费使用的识别次数多很多

### 插入图片问题

这个问题还是会挺困扰博客新手的，因为一般都是在本地编辑器编写markdown文件然后再上传，但是这样问题来了，图片是保存在本地的，一旦上传了markdown文件，图片路径就找不到了，因此目前解决思路大致有以下几种：

1. 将图片通过在线工具转换成base64编码，并用![image] (base64)格式进行插入，但是这样的话base63篇幅很长，不美观。
2. 第二种思路，利用图床（我没深究过）
3. 利用github，这个是我认为最好的方式了。大致的做法是把你所需要上传的图片保存在github的仓库中，例如你的图片路径为在 my仓库/img/14webp..jpg  中，这个时候在markdown写路径的时候**不要写上面那个路径**,会读取不到图片的！！！要进入github找到那个图片，打开之后，鼠标右键，复制图片的地址，然后再把图片地址插入到markdown文件即可。
![](https://github.com/Zengpeizhi/Zengpeizhi.github.io/blob/master/img/markdown2.jpg?raw=true)
### 最后推荐一个markdown写作软件 Typora
**简单容易上手！！！**


