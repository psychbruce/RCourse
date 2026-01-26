# 《R语言》课程代码文档

## 课程大纲与代码文档索引

[课程大纲 Syllabus 2026](https://psychbruce.github.io/RCourse/Syllabus_R-Programming_BaoHWS_2026Spring.pdf) \| [云盘资料](https://share.weiyun.com/o0kwn42K)\
（本课程不依赖PPT，以每章代码文档的实践学习为主）

### 第一模块：入门与筑基（共4周，8学时）

-   [第1章：基础入门（4学时）](https://psychbruce.github.io/RCourse/Chap01)（随堂作业1 & 2）
-   [第2章：函数对象（2学时）](https://psychbruce.github.io/RCourse/Chap02)（随堂作业3）
-   [第3章：数据结构（2学时）](https://psychbruce.github.io/RCourse/Chap03)（随堂作业4）

### 第二模块：处理与操作（共4周，8学时）

-   [第4章：字符处理（2学时）](https://psychbruce.github.io/RCourse/Chap04)（随堂作业5）
-   [第5章：变量计算（2学时）](https://psychbruce.github.io/RCourse/Chap05)（随堂作业6）
-   [第6章：数据操作（4学时）](https://psychbruce.github.io/RCourse/Chap06)（个人阶段作业①）

### 第三模块：统计与分析（共4周，8学时）

-   [第7章：基础统计（2学时）](https://psychbruce.github.io/RCourse/Chap07)（随堂作业7）
-   [第8章：方差分析（2学时）](https://psychbruce.github.io/RCourse/Chap08)（随堂作业8）
-   [第9章：回归分析（4学时）](https://psychbruce.github.io/RCourse/Chap09)（个人阶段作业②）

### 第四模块：数据可视化（共4周，8学时）

-   [第10章：绘图初阶（4学时）](https://psychbruce.github.io/RCourse/Chap10)（随堂作业9）
-   [第11章：绘图中阶（2学时）](https://psychbruce.github.io/RCourse/Chap11)（随堂作业10）
-   [第12章：绘图高阶（2学时）](https://psychbruce.github.io/RCourse/Chap12)（个人期末大作业）

注：每章对应一个代码文档（R Markdown运行导出的HTML网页），点击章节进入浏览，然后可从右上角“Code” → “Download Rmd”下载原始代码文件。

## 课程目标

1.  熟练掌握R语言的基础编程代码与各类数据处理操作。
2.  学会使用R包/函数实现数据统计分析，能正确解释结果。
3.  理解数据可视化的要求，灵活运用R语言完成各类科学绘图。
4.  批判认识AI生成代码的局限性，具备R代码的评鉴与迁移能力。

## 其他参考资料

-   《R语言编程指南》，任坤 著，人民邮电出版社（2017.10）
-   《R语言编程：基于tidyverse》，张敬信 著，人民邮电出版社（2023.2）
    -   PPT与数据集：<https://github.com/zhjx19/introR>
-   《R for Data Science》开源免费在线英文教材
    -   1e（2017.1）：<https://r4ds.had.co.nz/>
    -   2e（2023.6）：<https://r4ds.hadley.nz/>
-   R软件与R包帮助文档
    -   R官网与软件下载：<https://www.r-project.org/>
    -   RStudio编辑器下载：<https://posit.co/download/rstudio-desktop/>
    -   R包速查参考手册：<https://posit.co/resources/cheatsheets/>
    -   bruceR包在线文档：<https://psychbruce.github.io/bruceR/>
    -   data.table包在线文档：<https://rdatatable.gitlab.io/data.table/>
    -   ggplot2包在线文档：<https://ggplot2.tidyverse.org/>
    -   补充资料
        -   data.table与dplyr对比：[English](https://atrebas.github.io/post/2019-03-03-datatable-dplyr/)
        -   data.table与pandas对比：[English](https://atrebas.github.io/post/2020-06-14-datatable-pandas/), [中文](https://cosx.org/2021/01/dt-pd/)
        -   R作图参考：<https://r-graph-gallery.com/>
-   本课程代码文档R Markdown配置
    -   网页CSS样式：<https://psychbruce.github.io/RCourse/RmdCSS.css>
        -   另存为文件，放于Rmd文档同级别目录，并在下方代码中配置
    -   Rmd文档属性配置模板（用于Rmd文档开头位置）

```         
---
title: "标题"
subtitle: "副标题"
author: "姓名"
date: "`r Sys.Date()`"
output:
  html_document:
    toc: true
    toc_depth: 3
    toc_float:
      collapsed: false
      smooth_scroll: false
    code_download: true
    anchor_sections: true
    highlight: pygments
    css: RmdCSS.css
---
```

-   网络爬虫基础工具：网页CSS元素选择器
    -   [SelectorGadget](javascript:(function()%7Bvar%20s=document.createElement('div');s.innerHTML='Loading...';s.style.color='black';s.style.padding='20px';s.style.position='fixed';s.style.zIndex='9999';s.style.fontSize='3.0em';s.style.border='2px%20solid%20black';s.style.right='40px';s.style.top='40px';s.setAttribute('class','selector_gadget_loading');s.style.background='white';document.body.appendChild(s);s=document.createElement('script');s.setAttribute('type','text/javascript');s.setAttribute('src','https://dv0akt2986vzh.cloudfront.net/unstable/lib/selectorgadget.js');document.body.appendChild(s);%7D)();)（将这个超链接拖拽到你的浏览器书签栏，即可使用）
        -   [使用教程](https://selectorgadget.com/)
