# fq-book

|[![cc](https://i.creativecommons.org/l/by-nc/4.0/80x15.png)](http://creativecommons.org/licenses/by-nc/4.0/)|[![fq-book](https://img.shields.io/badge/%F0%9F%93%96book-fq--book-red.svg?longCache=true&style=flat-square)](https://hoodiearon.github.io/fq-book)|[![docsify](https://img.shields.io/badge/%F0%9F%93%96docs-docsify-brightgreen.svg?longCache=true&style=flat-square)](https://docsify.js.org/)|[![blog](https://img.shields.io/badge/%F0%9F%94%97blog-hoodiearon-lightgrey.svg?longCache=true&style=flat-square)](https://hoodiearon.github.io/)|[![outlook](https://img.shields.io/badge/%F0%9F%93%A7hotmail-@邮箱联系-blue.svg?longCache=true&style=flat-square)](mailto:hoodiearon@outlook.com)|[![telegram](https://img.shields.io/badge/telegram-:me-blue.svg?longCache=true&style=flat-square)](https://t.me/hoodiearon)
|:-:|:-:|:-:|:-:|:-:|:-:|

## intro

首先对早期fork者说声歉意，因为早期不管是[websiteful](https://github.com/hoodiearon/WebSiteUseful)还是[fq-book](https://hoodiearon.github.io/fq-book)变动都很大。特别是fq-book，也是各种担心且因其他缘由与相关操作不当导致删除重建好几次该书项目，致使该书有多个未完全残缺版本，很是影响阅读体验，这对该书籍传播是尤为不利的；知识是共享的，且该书转载与借鉴了很多相关作者的文章内容，因此允许演绎作品共享但禁止商用，你也可以下载源码进行[本地部署阅读本书](https://github.com/hoodiearon/fq-book/blob/master/tutorial/docsify-serve.md)。

因清空项目与删库的缘故，在了解IPFS不可更改与删除且永久保存的特性之后，用gitbook构建了fq-book与websiteuseful并已上传至IPFS平台，与此同时还生成了相关的短链接：

  * fq-book：https://tinyurl.com/y8b2n8bk
  
  * websiteuseful：https://tinyurl.com/ycqnkgc6

  * 相关源码以及其他资源：https://tinyurl.com/ydxylng9

写此教程目的在于尽力而为消除使用科学上网工具的门槛，让更多的人可以通过此方法与技巧连接免费自由的互联网；技巧与方法以及工具的基本使用流程，基本上算是说完了；这其中很多都是触类旁通的，掌握了书中这些技巧与方法，以后面对新事物也是可以快速上手的；现如今没必要再写下去了，现今且长期以答疑为主，如有疑难可以在本书项目中发起相关issues。

网络其实是填不完复杂到极点的坑,我觉得要一个非专业且追求免费的网络自由的人来说，面对一个强大的权势与顶尖的科技集于一身的GFW，本身就是一种不公平；这些本来是用来享受畅玩乐趣的，结果到国内却需要掌握足够的专业知识与拥有较长的实操经验，变成了耗时耗精力且极其折腾的一件事，不得不说这是种无F可说的悲哀...

此书献给热爱互联网的人们，但你若是党派喉舌的工作成员，不应该把闲暇时间浪费在这样一部毫无价值的书上，再见！

## ***mind you:*** 
由于工作和学习第二语言（非计算机）以及制作[LostMandarin](https://github.com/hoodiearon/LostMandarin)等方面的原因，有兴趣的话，支持一下，给[LostMandarin](https://github.com/hoodiearon/LostMandarin)打赏个star，非常感谢你们；没有额外的时间来一直更新，因此在这里给出额外的tips.

tips:

* 本书的 v2ray-4-heroku 操作，可能会有封禁的风险，但搭建ss爬虫代理网站不会存在该风险
* [glyptodon](https://demo.glyptodon.com) 和 [rabb.it](https://www.rabb.it/) 的原理是相通的，不就是本地部署在网页里的一台电脑...
* 关于手机方面（安卓），最好买预装原生系统的非国产手机
  * 因为国产手机会阉割谷歌框架（GMS），良心一点可以在系统设置中开启GMS功能
  * 某爱国手机已被媒体曝光有监控后门且刷机及其困难，迟早要被集火
* telegram关注一下 [相关vpn评测](https://t.me/vpnchina)、[tg代理](https://t.me/TgProxies) ，会对番茄有所帮助，另外[账号圈](https://t.me/XRAcc)也有些额外的付费vpn体验账号分享
* 针对 crx_header_invalid 的解决方案：
 ```
 crx扩展格式修改成rar压缩格式 -> 解压rar全部文件到文件夹 -> 加载已解压的扩展程序 -> 选中这整个文件夹，即可
 ```
