---
layout: default
title:  "网页制作学习笔记"
date:   2017-12-07 23:45:15 +0800
categories: posts rwd
image:
  teaser: Desktop.jpg
  feature: Desktop.jpg
---

## 网站评价



[chenjaipeng.GITHUB.IO 开展个人学习网络](https://chenjaipeng.github.io/)

#大概下载了模板，一些大致的都改了，排版，背景，图片，logo等等方面。文章方面也有了改进，在个人作品集里面也加了自己的作品。
## 2018/01/04
大致完A, B, C

# 同行评审

## 何丽华
- 网页设计方面：过于单调
- 内容方面：内容有点少无法评判。
- 网站文件结构方面：目录名与档名设计不合理。因为用的都是老师的模板，用的都是老师的文档名，只是对内容进行了替换，但没有修改文档名，所以不知道怎么举例了。

## 廖贵真
- 网页设计方面：没有做更多的改变，文件档名也没有改变，直接将老师档名复制，例如："https://chenjaipeng.github.io/i18nl10n"
- 文档名尽量使用英文，例如："https://chenjaipeng.github.io/"
- 网页很多地方都没有进行更改，图片没有放到相对应的images文件，![](<img src="https://chenjaipeng.github.io/images/" alt="teaser" itemprop="image">)

## 梁剑舜
- 视觉设计-颜色和对比度:
  - 前景颜色：#595959 偏灰色 
  -    background-image: linear-gradient(rgba(255,255,255,0), rgba(255,255,255,0)),url("../images/bei_jingtu.jpg");
  -    对比度较高

## 林树斌
 - 图形加载效率：
  - - 最大的图片为images/timg.jpg,大小为1m，加载时间为719ms，超过500ms，图像体积大，是侧边导航栏的动态图，重要性不高，应该更换其余体积小的图片
  - - 余下的博文搭配照片，加载速度均为150ms以下，体积不大200kb-300kb，加载效率高。
 - - 总的网站加载时长1.38秒
## 蔡泽纯
-字形：字体设置过小如：    font-size: 16px;
    font-size: 1rem;
    line-height: 1.75;
    margin-bottom: 28px;
    margin-bottom: 1.75rem;
    margin-top: 1rem;
}<br>
-标题：楷体，难以阅读，为衬体如：    font-family: Kai,Kaiti SC,KaiTi,DFKai-SB,BiauKai,\\6977\4F53,\\6977\4F53_GB2312,Songti SC,Georgia,Times,"Times New Roman",serif;<br>
-非标题：字体与标题一样是楷体，如：font-family: Kai,Kaiti SC,KaiTi,DFKai-SB,BiauKai,\\6977\4F53,\\6977\4F53_GB2312,Songti SC,Georgia,Times,"Times New Roman",serif;让人产生视觉疲劳，建议换成微软雅黑<br>
## 陈丽媛
- 网页的背景与字体比较比较没有突出，建议改变背景。有些图片加载不出。
## 林家慧
- 前景色和背景色对比不明显
- 学习笔记分类不明确

## 吴心丹
- 文章链接不到，需要改进
- 字体颜色可以做进一步修整，





### ### <div class="tiles">{% for post in site.categories.rwd %}{% include post-grid.html %}{% endfor %}</div>