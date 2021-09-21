---
layout: default
title: Learning Guide
parent: Misc 
nav_order: 1
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

R语言在统计分析和图形化展示方面具有独到的优势，在生物信息学和基因组学研究中广泛应用，我们必须对R语言和常用的package有足够的了解，才能在将来的工作中得心应手。中文教程可参考《R语言数据分析与可视化从入门到精通》，虽然书是最近出版的，但是其中讲到部分包已经有些过时可以略过。还有很多网络资源可以利用：

R语言入门

- An Introduction to R ([HTML](https://cran.r-project.org/doc/manuals/r-release/R-intro.html),  [PDF](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf), [EPUB](https://cran.r-project.org/doc/manuals/r-release/R-intro.epub))（官方简介；推荐先看这个）
- [R for Data Science](https://r4ds.had.co.nz/index.html) （用当下流行的package介绍R；推荐后看）
- [STAT 545: Data wrangling, exploration, and analysis with R](https://stat545.com/) （可选看）

R语言绘图

- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) （一位进化生物学和计算生物学领域的专家写的书；非常不错）
- [ggplot2: elegant graphics for data analysis](https://ggplot2-book.org/) （ggplot2的作者写的书） 

R语言进阶

- [Advanced R](https://adv-r.hadley.nz/) (R语言的深入剖析，看一看没坏处)

需要掌握的常用package

- `data.table`
- `ggplot2`
- `tidyverse`系列 - `dplyr` + `tidyr` + `readr`等

<br/>

##### 生物信息学

学校应该有相关的课程，但是可以参考这些网络资源作为辅助或者提前了解：

- [Coursera - 生物信息学: 导论与方法](https://www.coursera.org/learn/bioinformatics-pku) （高歌、魏丽萍老师）
- [基因组学分析](http://3d-genome.life/?page_id=7) （李程老师）
- 中国大学MOOC - 生物信息学（魏天迪等四位老师）

<br/>

##### 概率统计

应该尽量在本科阶段学习高等数学，线性代数，概率论和数理统计；如果只学了高数也没关系，抽时间自学另外两门课就可以了。除此之外，推荐这些书籍，可以作为补充学习的材料，也可以作为参考，需要时查阅：

- 白话统计 （用通俗易懂的语言介绍常用的统计学方法）
- [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)
- [An Introduction to Statistical Learning](https://www.statlearning.com/)
- [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/)

另外，最近深度学习在生物学中的应用越来越多，感兴趣的话可以自己找资料学习。更多相关图书请看本站Books页面。

<br/>

##### 演化生物学

演化生物学的理论由于需要比较多的概率和统计知识，大学里面的课程一般都不怎么深入，或者很难在一学期的课程里讲明白，好在这一领域的前辈们写的书足够的详细。

群体遗传学方面，推荐下面这几本书。第一本书是简介性的（也有一定难度），跟其他这一主题的教材相比，写的更加流畅，容易理解。第二本书更加详细，可以作为进一步学习的参考。如果想看更理论一些的书可以看本站Books页面。

- [An Introduction to Population Genetics: Theory and Applications](https://global.oup.com/ushe/product/an-introduction-to-population-genetics-9781605351537) by Rasmus Nielsen and Montgomery Slatkin 
- [Theoretical Evolutionary Genetics](https://felsenst.github.io/pgbook/pgbook.html) by Joseph Felsenstein

分子进化方面只推荐下面这一本书，从基本的理论知识到常用软件的算法写的非常详细，仅看前几章就让人受益匪浅。不论是学习分子进化的知识还是只想了解一下PAML、HyPhy等工具的原理，都很有帮助：

- [Molecular Evolution: A Statistical Approach](http://abacus.gene.ucl.ac.uk/MESA/) by Ziheng Yang

以下是领域内多位专家联合编写的分子进化和群体遗传学方面的手册，内容较新，并且涉及很多近年出现的应用，可以作为参考：

- [Phylogenetics in the Genomic Era](https://hal.inria.fr/PGE/)
- [Handbook of Statistical Genomics, 4th Edition](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119487845) （此书好像没有开放获取的版本，看学校有没有买了）



----

##### 其他培养方案供参考

[Guideline-for-Computational-Biology-and-Bioinformatics](https://github.com/gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics) （高歌老师组的研究生培养方案）



-----

© 2021 GxE Lab

