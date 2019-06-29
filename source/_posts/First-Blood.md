title: First Blood
date: 2016-02-15 18:16:45
tags: [life, code]
---

在下午打了数把dota后，想起了周一搭的hexo，于是去换了一个[yilia](https://github.com/litten/hexo-theme-yilia)的主题,顺便拿出了github上的头像。由于只是给自己看，就去掉了rss和一些评论插件。总的来说，hexo搭起来还是很方便的，我也总是算是有了自己一片自留地。<!-- more -->

### 搭建步骤

基本上是模仿简书上[HEXO+Github,搭建属于自己的博客](http://www.jianshu.com/p/465830080ea9)的步骤。配置一些基本的node模块，然后关联上我的github。最后把封藏很久的域名\(kkbsh.com\)解析到了这里。
稍微值得注意的是每次

```bash
$hexo generate
```
后都是重新生成一遍代码，所以一些不变的文件都要放在source文件下，这样每次都会提交到git上去。

2016-02-21 ，写完了，外面也下雨啦，又要叫外卖啦。

2019-04-11,  三年前太过仓促，现在又来补全一些功能。

```bash
hexo server -d

hexo deploy
```

