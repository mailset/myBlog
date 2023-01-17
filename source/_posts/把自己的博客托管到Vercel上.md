---
title: 把自己的博客托管到Vercel上
date: 2023-01-17 17:20:26
tags:
  - 技术
  - 博客
  - Hexo
---

今天把这个博客的托管商换成了[Vercel](https://vercel.com)，这个更快，更方便，只不过官网甚至没有IPv6（不过为啥我nslookup解析出来为啥有）

## 从Github Page转换成Vercel

这个需要把整个构建前(不是public目录)上传到github(gitlab也行)上，每次push会自动构建（还挺方便的）
温馨提示一下，git init之后会不上传子仓库，我的建议是直接删除子仓库的.git目录，比如git clone下来的主题，在hexo根目录下这样删除(linux bash)

```bash
rm -rf themes/你的主题/.git
```

接着创建仓库上传就可以了

然后来到[Vercrl官网](https://vercel.com)，直接通过Github(或者Gitlab)登录，授权，然后选择你放hexo的仓库(不是github page)，会自动识别Hexo或者其他的博客框架，继续输入Project Name，设置Build & Development Settings，就像这样

![构建设置](https://s2.loli.net/2023/01/17/ArXaBqpyilHSQgm.jpg)

接着翻到最下面点Deploy就可以了，此时你的博客应该就可以使用他提供的地址正常访问了。但博主的不能，也不知道出了什么问题，所以我添加了自定义域名，接着往下看

## 添加自定义域名

添加自定义域名也很简单的
进入Project，点击上面的Settings，出来Project Settings之后，点击左边的Domains，输入你需要添加的域名，然后再点击Add，下面放图片

![add前](https://s2.loli.net/2023/01/17/7rZMxtgeIWVmfYR.jpg)

点击add后，如果你添加的二级域名是www或者直接是根域名，会弹出一个弹窗，我的建议是选第三个，然后分别添加解析。其他的二级域名不会出现这个弹窗
接着就会出现这个

![add后](https://s2.loli.net/2023/01/17/jfxuEvKoYVPIgrQ.jpg)

这时直接去你的托管商添加CNAME记录就可以，如果是添加的根域名就按照提示添加A解析就可以了
此时你的博客已经成功托管到了Vercel上面，创建文章直接这样

```bash
hexo n 文章名字
git add .
git commit -m "要commit的文字"
```

Vercel会自动检测仓库更新，不用手动检查(其实我还是感觉检查一下更舒服)

至此，教程完毕。下面是一些小提醒

(P.S 改天可能会出Hexo创建博客的教程)

## 提醒

+ 如果是Cloudflare的服务，我不建议开启CDN(也就是代理)，这样会直接降低访问网站速度，~~并且DDoS的也不是你的服务器，你慌什么~~直接在创建记录的时候把代理状态关闭就可以
+ 本教程制作不易，~~而且博主还有作业没有写~~如果你喜欢的话，欢迎转发和评论，并且右边也有聊天室，欢迎来聊天，~~不过可能没人~~我们下次再见吧！
