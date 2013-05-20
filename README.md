基于BlogMi项目 的二次开发
======================

![特点：轻巧、方便](http://haow.in/blogmi/images/icon1.jpg)

特点：轻巧、方便
-------------
“博客迷”（BlogMi）是一套基于PHP语言的开源、简洁、高效的博客程序，它满足个人博客必要的建站需求，剔除了常见博客程序复杂臃肿的功能。因此，“迷”取令人着迷、迷你之意。

“博客迷”不需要数据库的支持，采用的是类似TXT文本数据库的存储形式。上传本程序到支持PHP的主机或虚拟空间，立即就可使用。博客内容的备份和还原非常方便，只需下载和上传程序目录下的全部文件即可，所有的文章、配置等均可完整保留和再现。

![功能：文章、页面](http://haow.in/blogmi/images/icon2.jpg)
功能：文章、页面
-------------
从功能上来说，“博客迷”分为“文章”和“页面”。

“文章”功能让你能够发布文章，仅保留基本的标题、标签、正文、发布时间等功能。发布文章时可以选择是否允许评论，这样在你添加了第三方的评论代码之后，可以针对每一篇文章设置评论权限。另外，还有发布状态的选项，允许你暂时把文章保存在草稿箱中。

“页面”功能让你可以自由创建一些独立页面，并且可以自定义链接，同时也像“文章”一样可设置评论权限、发布状态。

![安装：上传、配置](http://haow.in/blogmi/images/icon3.jpg)
安装：上传、配置
-------------
安装“博客迷”只需两步：

1. 将本程序解压上传到你的网站目录（不要求必须是根目录）；

2. 进入程序管理后台修改密码和网址，http://网站目录/admin/，默认帐号：admin，默认密码：2046。

然后开始使用吧！


二次开发目的
=============
1. 增加url redirect，除去url中的?参数，并支持自定义文章url
2. 修复遇到的一些Bug

TODO
=============
1. 增加代码高亮
2. 根据喜好修改样式


BlogMi官网地址:http://haow.in/blogmi

二次开发项目作者Blog:http://jack-y.com