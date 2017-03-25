---
title: bolg使用说明
date: 2017-03-25 13:46:33
tags: 
- 使用
- 说明
---

## 开始写第一篇博客
- 在`应用程序`->`实用工具`里找到一个叫`终端`的工具，打开它。
- 在终端里进入博客目录，操作步骤如下:
> 把博客文件夹拖到`终端`上会有一个路径（例如：`/Users/HD/Documents/kapok`）
> 复制这个路径，然后回车另一起行输入 `cd` 然后空格，再把刚才的路径粘贴上去（例如:`cd /Users/HD/Documents/kapok`）
- 继续另起一行输入 `hexo new 'bolg标题'`（例如：`hexo new 'blog使用说明'`），这个时候生成这篇文字模板，提示：`INFO  Created: ~/Documents/kapok/source/_posts/blog使用说明.md`
- 然后打开这个文件，kapok->source->_post目录下打开`blog使用说明.md`
- 在里面编辑输入文字
- 完成文字编辑之后，回到终端上输入 `hexo g d`  即可完成部署
- 以上基本操作，编写发布一篇博客

## 修改关于页面
kapok->source->about 目录下，打开index.md 进行编辑，编辑完成回到终端上输入 `hexo g d`  即可



