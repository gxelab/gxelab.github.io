---
layout: page
title: Learning
nav_order: 7
permalink: /learning/
---

<br/>

### 研究生基本知识和技能学习指南

<br/>

基础知识和编程能力是开展科学研究的必备条件，这里结合我们的研究，推荐一些相关的学习内容和资源，精力有限，这些资源不一定是最理想的，后续会逐步完善。



##### Linux

如果使用Linux和Mac OS操作系统，可以直接在终端（Terminal）练习命令行的操作。如果使用Windows系统，可以用虚拟机，也可以从Windows应用商店安装Ubuntu子系统学习。

我们的学习目的只是为了使用Linux运行一些专业的生物信息学软件，利用R或者python做数据分析，而不是成为专业的Linux系统管理员或者工程师，因此只需要有基本知识并了解常用的命令即可。相关的网络资源有很多，这里我们推荐：《Linux命令行大全-第二版》(The Linux Command Line, 2nd edition)。可以跟着教程快速过一遍，没有必要死记硬背，在电脑上多加练习即可。掌握怎么查询每个命令的使用方法（`cmd -h`;  `man cmd`;百度谷歌），以后需要的时候可以快速找到帮助，多用几次就熟悉了。

<br/>

##### R

R语言在统计分析和图形化展示方面具有独到的优势，在生物信息学和基因组学研究中广泛应用，我们必须对R语言和常用的package有足够的了解，才能在将来的工作中得心应手。中文教程可参考《R语言之书-编程与统计》(英文版书名为The Book of R: A First Course in Programming and Statistics)。还有很多网络资源可以利用：

R语言入门

- An Introduction to R ([HTML](https://cran.r-project.org/doc/manuals/r-release/R-intro.html),  [PDF](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf), [EPUB](https://cran.r-project.org/doc/manuals/r-release/R-intro.epub))（官方简介；推荐先看这个）
- **[R for Data Science](https://r4ds.had.co.nz/index.html)** （用当下流行的package介绍R；推荐后看）
- [STAT 545: Data wrangling, exploration, and analysis with R](https://stat545.com/) （可选看）
- [R Programming for Data Science](https://bookdown.org/rdpeng/rprogdatascience/)

R语言绘图

- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) （一位进化生物学和计算生物学领域的专家写的书；非常不错）
- [ggplot2: elegant graphics for data analysis](https://ggplot2-book.org/) （ggplot2的作者写的书） 

R语言进阶

- **[Advanced R](https://adv-r.hadley.nz/)** (R语言的深入剖析，看一看没坏处)

需要掌握的常用第三方package

- `tidyverse`系列 - `dplyr` + `tidyr` + `readr`+`readxl`等
- `ggplot2`
- `data.table` (`dplyr+tidyr`和d`ata.table`二选一)

R语言代码书写规范：

- [The tidyverse style guide](https://style.tidyverse.org/)

<br/>

##### Python

网上有无数免费的python学习资源。如果跟着书学的话，[这里](https://nostarch.com/catalog/python)有几本不错的入门书籍，包括：

- Python Crash Course, 2nd Edition: A Hands-On, Project-Based Introduction to Programming
- Real-World Python: A Hacker's Guide to Solving Problems with Code

专门讲如何用python做数据分析的书包括：

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

##### 生物信息学

学校应该有相关的课程，但是可以参考这些网络资源作为辅助或者提前了解：

- [Coursera - 生物信息学: 导论与方法](https://www.coursera.org/learn/bioinformatics-pku) （高歌、魏丽萍老师）
- [基因组学分析](http://3d-genome.life/?page_id=7) （李程老师）
- [Coursera 生物信息学专项课程](https://www.coursera.org/specializations/bioinformatics)

一些不错的参考书：

- **Biological sequence analysis - Probabilistic models of proteins and nucleic acids**
- Bioinformatics and Functional Genomics （中文书名《生物信息学与功能基因组学》第三版）
- 生物信息学（第二版，樊龙江主编）

<br/>

##### 概率统计

应该尽量在本科阶段学习高等数学，线性代数，概率论和数理统计；如果只学了高数也没关系，抽时间自学另外两门课就可以了。可以从这几本书开始：

- A First Course in Probability （中文书名《概率论基础教程》）
- Statistical Inference, 2nd edition （George Casella, Roger L. Berger；中文书名《统计推断》）
- Introduction to Probability Models （中文书名《应用随机过程：概率模型导论》）

除此之外，推荐这些书籍，可以作为补充学习的材料，也可以作为参考，需要时查阅：

- **[The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)** （包含大量如何在R中实现的例子）
- [An Introduction to Statistical Learning](https://www.statlearning.com/)
- [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/)
- **[Deep Learning](https://www.deeplearningbook.org/)**

另外，最近深度学习在生物学中的应用越来越多，感兴趣的话可以自己找资料学习。

<br/>

##### 演化生物学

演化生物学的理论由于需要比较多的概率和统计知识，大学里面的课程一般都不怎么深入，或者很难在一学期的课程里讲明白，好在这一领域的前辈们写的书足够的详细。

群体遗传学方面，推荐下面这几本书。前两本书是简介性的（也有一定难度），跟其他这一主题的教材相比，写的更加流畅，容易理解。第三本书更加详细，也更难，可以作为进一步学习的参考。

- **[An Introduction to Population Genetics: Theory and Applications](https://global.oup.com/ushe/product/an-introduction-to-population-genetics-9781605351537)** by Rasmus Nielsen and Montgomery Slatkin 
- **[Molecular Population Genetics](https://global.oup.com/academic/product/molecular-population-genetics-9780878939657)** by Matthew William Hahn
- [Mathematical Population Genetics](https://link.springer.com/book/10.1007/978-0-387-21822-9) by Warren J. Ewens
- [Probability Models for DNA Sequence Evolution](https://www.springer.com/gp/book/9780387781686) by Richard Durrett
- Coalescent Theory: An Introduction By John Wakeley

分子进化方面只推荐下面这一本书，从基本的理论知识到常用软件的算法写的非常详细，仅看前几章就让人受益匪浅。不论是学习分子进化的知识还是只想了解一下PAML、HyPhy等工具的原理，都很有帮助：

- **[Molecular Evolution: A Statistical Approach](http://abacus.gene.ucl.ac.uk/MESA/)** by Ziheng Yang

以下是领域内多位专家联合编写的分子进化和群体遗传学方面的手册，内容较新，并且涉及很多近年出现的应用，可以作为参考：

- [Phylogenetics in the Genomic Era](https://hal.inria.fr/PGE/)
- [Handbook of Statistical Genomics, 4th Edition](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119487845)

<br/>

### 科研训练

#### 学术交流

- 如何准备学术报告的ppt：[Designing Effective Scientific Presentations](https://www.ibiology.org/professional-development/scientific-presentations/)



#### 文献阅读

- [How to (seriously) read a scientific paper](https://www.science.org/careers/2016/03/how-seriously-read-scientific-paper)
- [How to read and understand a scientific paper: a guide for non-scientists](https://blogs.lse.ac.uk/impactofsocialsciences/2016/05/09/how-to-read-and-understand-a-scientific-paper-a-guide-for-non-scientists/)
- [Infographic: How to read a scientific paper](https://www.elsevier.com/connect/infographic-how-to-read-a-scientific-paper)



----

##### 相关资源

- [Guideline-for-Computational-Biology-and-Bioinformatics](https://github.com/gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics) （高歌老师组的研究生培养方案）
- [培养和锻炼成员的职业技能](http://3d-genome.life/)(李程老师分享的科研职业技能培训资料)
- [HarvardX Biomedical Data Science Open Online Training](https://rafalab.github.io/pages/harvardx.html)
- [Modern Statistics for Modern Biology](https://web.stanford.edu/class/bios221/book/index.html)



-----

© 2021 GxE<sup>2</sup> Lab

