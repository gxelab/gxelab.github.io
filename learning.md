---
layout: page
title: Learning
nav_order: 7
permalink: /learning/
---

<br/>

### 研究生基本知识和技能学习指南 (v2024)

> 相关资料获取：坚果云团队版/GxELab/Resources/Library/推荐参考书

<br/>


##### 01. Linux

如果使用Linux和Mac OS操作系统，可以直接在终端（Terminal）练习命令行的操作。如果使用Windows系统，可以用虚拟机，也可以从Windows应用商店安装Ubuntu子系统学习。

> [使用 WSL 在 Windows 上安装 Linux](https://learn.microsoft.com/zh-cn/windows/wsl/install)

我们的学习目的只是为了使用Linux运行一些专业的生物信息学软件，利用R或者python做数据分析，而不是成为专业的Linux系统管理员或者工程师，因此只需要有基本知识并了解常用的命令即可。相关的网络资源有很多，这里我们推荐：《Linux命令行大全-第二版》(The Linux Command Line, 2nd edition)。可以跟着教程快速过一遍，没有必要死记硬背，在电脑上多加练习即可。掌握怎么查询每个命令的使用方法（`cmd -h`;  `man cmd`;百度谷歌），以后需要的时候可以快速找到帮助，多用几次就熟悉了。


> 自查清单：https://gitee.com/mt1022/bioinfo_tutorials/blob/master/basics/Linux.md

<br/>

##### 02. R

R语言在统计分析和图形化展示方面具有独到的优势，在生物信息学和基因组学研究中广泛应用，我们必须对R语言和常用的package有足够的了解，才能在将来的工作中得心应手。

R语言入门

- **An Introduction to R** ([HTML](https://cran.r-project.org/doc/manuals/r-release/R-intro.html),  [PDF](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf))（官方简介；推荐先看这个）
- **[Advanced R](https://adv-r.hadley.nz/)** (R语言的深入剖析，想把R用的得心应手必看)
- **[R for Data Science (2e)](https://r4ds.hadley.nz/)**（R语言数据分析的基础；推荐后看）

其他参考资料

- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) （怎么做合理、美观的可视化）
- [ggplot2: elegant graphics for data analysis](https://ggplot2-book.org/) （ggplot2的作者写的书） 
- [STAT 545: Data wrangling, exploration, and analysis with R](https://stat545.com/) 
- [R Programming for Data Science](https://bookdown.org/rdpeng/rprogdatascience/)


需要掌握的常用第三方package

- `tidyverse`系列 - `dplyr` + `tidyr` + `readr`+`ggplot2`等
- `data.table`

`dplyr`, `tidyr`, `readr`和`ggplot2`需要非常熟练。


<br/>

##### 03. Python

网上有无数免费的python学习资源，B站也有很多视频教程，根据自己的喜好选择一个即可，重要的是得上手练，不能只看。专门讲如何用python做数据分析的书包括：

- **[Python for Data Analysis, 3E](https://wesmckinney.com/book/)** (注重数据分析，强烈推荐)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- Data Science from Scratch: First Principles with Python (2nd)

[JupyterLab](https://jupyter.org/)使得用python做数据分析更加方便。

需要掌握的常用第三方package

- [numpy](https://numpy.org/doc/stable/user/index.html#user)
- [pandas](https://pandas.pydata.org/docs/user_guide/index.html#user-guide)
- [matplotlib](https://matplotlib.org/stable/tutorials/index.html)

python代码书写规范

- [Style Guide for Python Code](https://peps.python.org/pep-0008/)

<br/>


##### 04. 概率统计

应该尽量在本科阶段学习高等数学，线性代数，概率论和数理统计；如果只学了高数也没关系，抽时间自学另外两门课就可以了。可以从这几本书开始：

概率

- **A First Course in Probability** （中文书名《概率论基础教程》）
- Introduction to Probability Models （中文书名《应用随机过程：概率模型导论》）

统计

- **Modern Mathematical Statistics with Applications** (Jay L. Devore, Kenneth N. Berk, Matthew A. Carlton; 3rd, 2021)
- [**Bayesian Data Analysis**](http://www.stat.columbia.edu/~gelman/book/)
- [**An Introduction to Statistical Learning**](https://www.statlearning.com/) （包含大量如何在R中实现的例子）
- [**Dive into deep learning**](https://d2l.ai/) (pytorch版)

除此之外，推荐这些书籍，可以作为补充学习的材料，也可以作为参考，需要时查阅： 

- [**Deep Learning**](https://www.deeplearningbook.org/)
- Statistical Inference, 2nd edition （George Casella, Roger L. Berger；中文书名《统计推断》）
- A Modern Introduction to Probability and Statistics: Understanding Why and How
- [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)

[StatQuest](https://statquest.org/video-index/)的视频讲各类统计学的概念非常直观，而且简单易懂，强烈推荐。

<br/>


##### 05. 分子细胞遗传基础

- **Molecular Biology of the Cell** (7e, 2022)
- 
如果你本科专业不是生物科学或生物技术，强烈建议阅读以上书籍快速了解相关的基础知识。即使你学的是相关专业，也可以通过本书获得更清晰的细胞内基本过程的图像。

<br/>


##### 05. 生物信息学

强烈推荐:

- [**Introduction to Bioinformatics and Computational Biology**](https://liulab-dfci.github.io/bioinfo-combio/)

其他网上资源:
- [Coursera - 生物信息学: 导论与方法](https://www.coursera.org/learn/bioinformatics-pku) （高歌、魏丽萍老师）
- [基因组学分析](http://3d-genome.life/?page_id=7) （李程老师）
- [Bioinformatics Tutorial](https://book.ncrnalab.org/teaching/) (清华鲁志老师)
- [Coursera 生物信息学专项课程](https://www.coursera.org/specializations/bioinformatics)
- [Modern Statistics for Modern Biology](https://web.stanford.edu/class/bios221/book/index.html)

不错的参考书:

- **Biological sequence analysis - Probabilistic models of proteins and nucleic acids**
- [**Bioinformatics Algorithms**](https://www.bioinformaticsalgorithms.org/)
- Bioinformatics and Functional Genomics （中文书名《生物信息学与功能基因组学》第三版）
- 生物信息学（第二版，樊龙江主编）

<br/>


##### 06. 演化生物学

群体遗传学方面，推荐下面这本书，内容比较连贯，容易理解，更深入或者复杂的内容请看其他参考书:

- [**An Introduction to Population Genetics: Theory and Applications**](https://global.oup.com/ushe/product/an-introduction-to-population-genetics-9781605351537) by Rasmus Nielsen and Montgomery Slatkin 

分子进化方面只推荐下面这一本书，从基本的理论知识到常用软件的算法写的非常详细:

- [**Molecular Evolution: A Statistical Approach**](http://abacus.gene.ucl.ac.uk/MESA/) by Ziheng Yang

以下是领域内多位专家联合编写的分子进化和群体遗传学方面的手册，内容较新，并且涉及很多近年出现的应用，可以作为参考手册：

- [Phylogenetics in the Genomic Era](https://hal.inria.fr/PGE/)
- [Handbook of Statistical Genomics, 4th Edition](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119487845)

其他参考书：

- [**Mathematical Population Genetics**](https://link.springer.com/book/10.1007/978-0-387-21822-9) by Warren J. Ewens
- [Molecular Population Genetics](https://global.oup.com/academic/product/molecular-population-genetics-9780878939657) by Matthew William Hahn
- [Probability Models for DNA Sequence Evolution](https://www.springer.com/gp/book/9780387781686) by Richard Durrett
- Coalescent Theory: An Introduction By John Wakeley
- Phylogenetic trees made easy： A how-to manual


<br/>


### 科研训练

#### 文献阅读

- [How to (seriously) read a scientific paper](https://www.science.org/careers/2016/03/how-seriously-read-scientific-paper)
- [How to read and understand a scientific paper: a guide for non-scientists](https://blogs.lse.ac.uk/impactofsocialsciences/2016/05/09/how-to-read-and-understand-a-scientific-paper-a-guide-for-non-scientists/)
- [Infographic: How to read a scientific paper](https://www.elsevier.com/connect/infographic-how-to-read-a-scientific-paper)


#### 学术交流

- 如何准备学术报告的ppt：[Designing Effective Scientific Presentations](https://www.ibiology.org/professional-development/scientific-presentations/)


#### 学术写作

- Scientific Writing and English for Academic Research ([416133001](https://chaosonglab.github.io/teaching/))


----

##### 相关资源

- [Guideline-for-Computational-Biology-and-Bioinformatics](https://github.com/gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics) （高歌老师组的研究生培养方案）
- [培养和锻炼成员的职业技能](http://3d-genome.life/)(李程老师分享的科研职业技能培训资料)
- [HarvardX Biomedical Data Science Open Online Training](https://rafalab.github.io/pages/harvardx.html)
- [进化之光云论坛](https://space.bilibili.com/527193889)
- [Tutorials on phylogenetic and phylogenomic inference](https://github.com/mmatschiner/tutorials)


-----

© 2024 GxE Lab

