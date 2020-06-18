---
title: hexo
categories:
  - hexo blog
tags:
  - hexo blog
date: 2020-06-18 16:33:25
---

# 一、 hexo 命令
[hexo 使用指南](https://hexo.io/zh-cn/docs/commands)
---
# 二、 新增文章
在source/_posts/dir_name目录下新增xxx.md文件，标题为title

`hexo new post -p dir_name/xxx "title"`
举例： hexo new post -p poem/zxs "致橡树"
---
使用本地图片：
本地图片放在images目录下，在md文档中使用以下格式获取图片
`![](/images/wechat.jpg)`
![](/images/wechat.jpg)

# 三、 发布部署
本项目已集成travis构建，新增文章后只需要push source分支到github即可，
travis会自动构建source分支代码，讲hexo build完的页面push到master分支。


 

