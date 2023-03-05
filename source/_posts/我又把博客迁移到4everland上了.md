---
title: 我又把博客迁移到4everland上了
date: 2023-03-05 17:00:00
top_img: https://dashboard.4everland.org/img/svg/logo.svg
cover: https://dashboard.4everland.org/img/svg/logo.svg
tags:
  - 技术
  - Web3
  - Serverless
  - IPFS
---

~怎么有人三迁博客啊（~

最开始是github pages，然后是Vercel， 现在又成了4everland，反正都挺好用，看自己喜好

## 讲在前面

上一次迁移的那篇文章是：[把自己的博客托管到 Vercel 上](https://mailset.top/2023/01/17/%E6%8A%8A%E8%87%AA%E5%B7%B1%E7%9A%84%E5%8D%9A%E5%AE%A2%E6%89%98%E7%AE%A1%E5%88%B0Vercel%E4%B8%8A/)

建议阅读上一篇文章再来阅读这一篇文章

## 开始迁移

去[4everland官网](https://www.4everland.org/)注册一个帐号，可以使用Github帐号登陆

接着会自动跳转到dashboard页面，页面右侧的栏中找到Hosting -> Projects，点进去，点击New Project， From Git/Template，授权你的GitHub帐号（注意，只能用Github，没有github的需要把其他地方的仓库迁移过去）

然后在下面是你的所有仓库，选择你博客的仓库（在上一篇有讲），点击Import，调整构建设置，我的是这样的：

![BuildConfiguration](https://img.mailset.top/ShareX/2023/03/msedge_uWWZ0nlFvw.png)

可以参考

最后等待他构建完成，就可以通过他给的地址访问了！

## 添加域名

相比大家都不想让别人知道你用的是4everland罢（bushi

如果想绑定自己的域名的话，就点击左边的Hosting -> Domains，然后点右上角的 Add，选择你要添加域名的那个网站，上面写你要添加的域名

顺便一提，可以添加中文域名，你需要在浏览器里输入你想要绑定的中文域名，之后复制一下地址栏，再粘贴到这里，去掉前面的http:// 就可以

就像这样

![你不觉得这很酷吗，很符合我对未来的想象](https://img.mailset.top/ShareX/2023/03/msedge_l2OtiRasGA.png)

第一个就是中文域名 ，对应的是 [博客.mailset.top](xn--9krq6q.mailset.top)

---

至此文章已经大致结束，如果有什么要补充的可以在下面评论，谢谢

那么希望这篇文章可以帮到你，再见

