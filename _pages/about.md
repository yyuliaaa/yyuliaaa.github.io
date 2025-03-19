# 自我介绍
东北农业大学（211）2022级数据科学与大数据技术专业的本科生，预计获得今年推免生名额。大一专注于扎实数学基础知识，大二对计算机视觉和深度学习领域产生强烈兴趣，自此投入了大量的时间和精力在深度学习的基础知识学习、实验运行、学习进度的总结与规划，同时每周与导师就研究进展和计划进行深入讨论。我坚信我对科研问题的好奇和对实现目标的毅力，将在在未来一直支持我进行学术研究。

## 教育背景
前5学期的智育学分绩为3.87248，智育排名位于专业前10%。在读期间的核心课程：数字图像处理(99)，大数据基础(98)，数据治理(97)，数据采集(96)，农业试验设计与数据分析(95)，概率论与数理统计(93)，数据挖掘(92)，数据库原理与应用(92)，高等代数与解析几何(92)，数学分析(90)，数据科学基础(90)，数据可视化(90)。已获得CET-4和CET-6证书(均为首考，CET-4：582分；CET-6：498分)

## 科研项目研究经验
在高等代数与解析几何课程教师的推荐下，大二下学期进入本院吴秋峰副教授的实验室开展科研项目，项目方向：智慧农业、计算机视觉、目标检测。在实验室的课题研究期间，不仅用实验室的数据集训练过多个目标检测模型，还对个别模型有创新点的实现。大三上学期初，以第一作者在老师指导方向的基础上独立完成了一篇目标检测领域综述的撰写。

大一通过实操三维建模的筛选进入数字化与智能化设计创新协会，大三基于研究成果：三维设计虚拟仿真教学系统，与导师共同完成论文：混合现实技术支持下三维设计教学系统创新与实践，现已返修。

## 论文方面成果
1. **独立一作** Fruit detection methods based on Deep Learning: A Systematic Literature Review，ieee access(SCI3区，JCR2区)，外审(2025.3.3)
   - 论文简介：系统性地探讨了深度学习在果实检测领域的研究进展，首次将果实检测难题解构为小样本、复杂、小目标与实时四类场景，并分别分析了四大困难场景基于深度学习的有效的改进方法，为果实检测研究提供了指南
   - 主要贡献：在导师指导下独立完成文献分析、图表绘制、论文撰写

2. **第二作者(导师第一)** 混合现实技术支持下三维设计教学系统创新与实践，农业工程(科技核心)，小修(2025.3.17)
   - 项目简介：以直角坐标机器人为典型案例，开发了一套模块化的基于混合现实技术的三维设计虚拟仿真教学系统，集成动态演示、虚拟拆装和实时反馈等功能，丰富了虚拟仿真与教学领域的研究
   - 主要贡献：在农业机械设计案例虚拟仿真APP的基础上添加学生操作数据分析、机械动态拆分重装功能，与导师共同完成论文撰写、图表制作
---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

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
