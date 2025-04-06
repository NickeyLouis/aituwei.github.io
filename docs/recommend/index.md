# 今日推荐(自动生成)

> 老胡的信息周刊**历史信息回顾**，主要针对计算机领域，内容主题极大程度被我个人喜好主导。这个项目核心目的在于记录让自己有印象的信息做一个**留存**以及**共享**。


## 🎯 项目 

### [crawlee](https://crawlee.dev/)

基于 `Node` 编写的开源网络爬虫库：

![crawlee](https://images-1252557999.file.myqcloud.com/uPic/crawlee.jpg) 

### [markdown-nice](https://github.com/mdnice/markdown-nice)

有很多朋友问我的公众号排版是怎么做的，答案就是`markdown-nice`开源项目：

> 支持主题设计的 Markdown 编辑器，让排版变 Nice

你可以选择直接访问[官方](https://editor.mdnice.com/)，也可以自建，自建的好处是不需要登录，下面截图就是我自建的：

![](https://images-1252557999.file.myqcloud.com/uPic/oGeICY.png)

官方并不支持`Docker`部署，为了方便大家使用，直接用我打包上传的镜像，一行命令即可体验`mdnice`:

```shell
docker run --name mdnice -p 8080:80 -d howie6879/mdnice:22.02.11
``` 

### [public-image-mirror](https://github.com/DaoCloud/public-image-mirror)

有一些 `Docker` 镜像托管在 `gcr.io`，这样国内下载就会很不方便，使用这个项目就可以快速下载，简单加个前缀就行：

```shell
k8s.gcr.io/coredns/coredns => m.daocloud.io/k8s.gcr.io/coredns/coredns
```

其他资源：

- 常用镜像仓库：[一些国内镜像源](https://gist.github.com/qwfys/aec4d2ab79281aeafebdb40b22d0b748)
- [x-mirrors/gcr.io](https://github.com/x-mirrors/gcr.io) 

## 🤖 软件 

### [Amarok-Hider](https://github.com/deltazefiro/Amarok-Hider)

Amarok 是一款轻量级隐私保护工具，一键隐藏你的隐私文件和应用:

- 简单易用: 文件应用，一键隐藏。
- 高速大文件隐藏: 只混淆文件名和文件签名，文件大小并不影响隐藏速度。
- 免 Root 应用隐藏: 从桌面隐藏应用程序。目前支持 Root、Shizuku、Dhizuku 和 DSM 模式。
- 老板键: 在紧急情况下使用浮动按钮隐藏应用和文件。
- 快捷开关: 控制中心开关，无需打开应用即可隐藏。
- 赏心悦目的界面: 简洁干净的 Material3 设计。

![Amarok](https://images-1252557999.file.myqcloud.com/uPic/Amarok.jpg) 

### [DingDongHelper](https://github.com/Skykai521/DingDongHelper)

安卓叮咚买菜抢菜插件，作者是个有大爱的人，针对上海疫情，开源了这款抢菜插件，在上海的朋友们，如果你买菜困难，可以用起来，同类型项目：

- [美团买菜版本](https://github.com/qulingyuan/robVeg)
- [叮咚买菜运力监控](https://github.com/jozhn/ddmc.monitor) 

### [Cloud Document Converter](https://github.com/lujunji4113/cloud-document-converter/tree/main)

一个 `Chrome` 扩展， 支持下载、复制飞书云文档为 `Markdown`：

![Cloud Document Converter](https://images-1252557999.file.myqcloud.com/uPic/ATwWi4.png) 

## 👀 资料 

### [itdevbooks/pdf](https://github.com/itdevbooks/pdf)

编程电子书，电子书，编程书籍，包括C，C#，Docker，Elasticsearch，Git，Hadoop，HeadFirst，Java，Javascript，jvm，Kafka，Linux，Maven，MongoDB，MyBatis，MySQL，Netty，Nginx，Python，RabbitMQ，Redis，Scala，Solr，Spark，Spring，SpringBoot，SpringCloud，TCPIP，Tomcat，Zookeeper，人工智能，大数据类，并发编程，数据库类，数据挖掘，新面试题，架构设计，算法系列，计算机类，设计模式，软件测试，重构优化，等更多分类 

### [jaywcjlove/handbook](https://github.com/jaywcjlove/handbook)

作者整理了自己学习过程中产生的笔记，需要快速学一些东西或者查找资源的时候可以看看：

![jaywcjlove_handbook](https://images-1252557999.file.myqcloud.com/uPic/jaywcjlove_handbook.jpg) 

### [Google 工程实践文档](https://jimmysong.io/eng-practices/)

Google 在 GitHub 开源的一份工程实践文档：《Google 工程实践文档》，此文档为 Google 工程师长期累积的最佳实践，希望通过这份文档，能帮助更多开发者完成代码审查工作，为项目代码提供标准参考。

![eng-practices](https://images-1252557999.file.myqcloud.com/uPic/rDrm0R.png) 

## 🕸 网站 

### [自建在线体验 Gemini Pro](https://gemini.fre123.com/)

老胡昨晚熬夜基于谷歌开放的 `Gemini Pro API` 和 `babaohuang` 的开源项目 [GeminiProChat](https://github.com/babaohuang/GeminiProChat)(这项目不错，大家可以关注下) 搭建了一套 `Gemini Pro`，大家来体验玩玩：

- [搭建文章](https://mp.weixin.qq.com/s/0FSltuCkaYJ0EFBxFtSYfA)
- Gemini Pro 体验地址：https://gemini.fre123.com/

![Xnip2023-12-22_14-12-10](https://images-1252557999.file.myqcloud.com/uPic/Xnip2023-12-22_14-12-10.jpg) 

### [pixabay](https://pixabay.com/)

`Pixabay` 是全球知名的图库网站及充满活力的创意社区，拥有上百万张免费正版高清图片素材，涵盖照片、插画、矢量图、视频等分类，你可以在任何地方使用 `Pixabay` 图库中的素材，无惧版权风险：

![pixabay](https://images-1252557999.file.myqcloud.com/uPic/pixabay.jpg) 

### [flomoapp](https://flomoapp.com/)

flomo是一款「思维工具」，主要目的是帮助你「记录想法的川流」，我个人用了大半年了，经常会在上面记录自己生活工作中的各种思考，于我而言非常有用，可以静静地输出自己的思考，而且其回顾功能会让我定期复盘再次思考，介意大家都来试试，可以点这里进行[注册](https://flomoapp.com/register2/?NDgzNTM)。

![flomoapp](https://images-1252557999.file.myqcloud.com/uPic/6G6qrd.jpg) 

## ✍️ 说明

周刊相关信息：

- 公众号：[老胡的储物柜](https://images-1252557999.file.myqcloud.com/uPic/ETIbMe.jpg)，欢迎加我微信进**周刊群聊**
- [TG 频道订阅](https://t.me/howie_weekly)：老胡周刊 TG 信息频道，对周刊的信息补充，会分享更多的资源，欢迎关注👏
- [聚合周刊](https://www.fre321.com/weekly)：老胡收集了国内外60+优质技术周刊进行信息聚合🔥
- Github 地址：[howie6879/weekly/](https://github.com/howie6879/weekly/)，觉得不错麻烦给我一个**Star**，谢谢 ❤️
- 浏览地址：[老胡的信息周刊](https://weekly.howie6879.com) | [今日推荐](https://weekly.howie6879.com/recommend/index.html) | [MacOS 软件推荐](https://weekly.howie6879.com/soft/mac.html)

🙌如果你阅读到这里，说明我们对信息的认可区域是有一定交集的，可以说我们是**同道中人**，所以如果你有自认为不错的信息获取渠道，欢迎**留言**或者**私聊**我，谢谢。