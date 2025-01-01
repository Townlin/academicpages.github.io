---
permalink: /
title: "关于我 About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

我是北京大学物理学院2023级本科生，我的研究兴趣包括量子计算，量子模拟。

I'm an undergrduate student from School of Physics, Peking University. My research interest includes quantum computation and quantum simulation( especially the physical realization of quantum computation).



一个正在搭建的个人学术主页 A self scholar-page in building
======
我在2024年12月31日突然想到要做一个自己的主页，于是马上着手，fork自GitHub上academicpage的仓库。

It occured to me that I wanted to build my own scholar-page on December 31, 2024, so I took action right away. This page is forked from academicpage on GitHub.


这里有什么 What's here
======
1. 由于这个网页才刚刚起步，里面没有太多内容，我会不断在网页上更新内容，来让页面更加充实。

   Now that this page is on halfway, there's not much content. I will continuously upload to enrich it.
2. 因为我暂时没时间去学习更多的网页技术，所以我没办法给主页加上中英文切换的功能，就只好手动给每条信息都列上中英文（虽然这样看上去非常愚蠢），并且由于我的英语水平有限，很可能充斥着语法错误。

   For reason that I don't have enough time to master more web technology, I can't add language switch function on homepage. So I have to manually list both Chinese and English (though reaaly stupid), and due to my poor English level, it could be filled with grammar mistakes.
3. 目前我还没有出版的论文或书籍，以后如果我有了发表的机会，我将更新在出版物栏目。

   I still don't have any published paper or book, if I do in the future, I will update them in Publications Column.
4. 讨论栏目里罗列的是我的组会或讨论课幻灯片/文档，点进去以后有下载链接。
   Talks Column contains slides of my conference or talk-class, you can get a download link after click in.
5. 我还没有想好文件夹放些什么东西，可能会变成我的云文件夹吧。

   I don't have any idea what to store in Portfolio Column, maybe it will become my next iCloud.
6. 我不知道大家都拿博客发些什么，可能我会发一些碎碎念，日常之类的东西，纯当做记事本了。

   I don't how others take Blog Posts, I would post some chattering, something concerned with my everyday life. Just a notebook.
7. 简历还在不断更新，目前只是个模版罢了。

   CV is still on its way, it's only a template now.
8. 导览是给我看的。

   The Guide Column is for me.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
