+++
title = "R: Programming Language"

date = 2016-04-20
lastmod = 2018-04-11
draft = false

tags = ["R"]

summary = "**We mainly use R for statistics and data analysis, so we briefly introduce R and related sources here.** <br/>R is a programming language and **free** software environment for statistical computing and graphics that is supported by the R Foundation for Statistical Computing. The R language is widely used among statisticians and data miners for developing **statistical software** and **data analysis**. <br/>R is a GNU package. The source code for the R software environment is written primarily in **C**, **Fortran**, and **R**.  R is freely available under the GNU General Public License, and pre-compiled binary versions are provided for various operating systems."

[header]
image = "headers/R5r.png"
caption = "Image credit: [**R**](https://www.r-project.org/)"
+++
---
<span id="jump"></span>
### What is R ?

<p align="justify">**R** is a language and environment for statistical computing and graphics. It is a GNU project which is similar to the S language and environment which was developed at Bell Laboratories (formerly AT&T, now Lucent Technologies) by John Chambers and colleagues. R can be considered as a different implementation of S. There are some important differences, but much code written for S runs unaltered under R.

<p align="justify">R provides **a wide variety of** statistical (linear and nonlinear modelling, classical statistical tests, time-series analysis, classification, clustering, …) and graphical techniques, and is highly extensible. The S language is often the vehicle of choice for research in statistical methodology, and R provides an Open Source route to participation in that activity.

<p align="justify">One of R’s strengths is the ease with which well-designed publication-quality plots can be produced, including mathematical symbols and formulae where needed. Great care has been taken over the defaults for the minor design choices in graphics, but the user retains full control.

<p align="justify">R is available as **Free Software** under the terms of the Free Software Foundation’s GNU General Public License in source code form. It compiles and runs on a wide variety of UNIX platforms and similar systems (including FreeBSD and Linux), Windows and MacOS.


### The R environment
<p align="justify">R is an integrated suite of software facilities for data manipulation, calculation and graphical display. It includes

* an effective data handling and storage facility,
* a suite of operators for calculations on arrays, in particular matrices,
* a large, coherent, integrated collection of intermediate tools for data analysis,
* graphical facilities for data analysis and display either on-screen or on hardcopy, and
* <p align="justify">a well-developed, simple and effective programming language which includes conditionals, loops, user-defined recursive functions and input and output facilities.

<p align="justify">The term “environment” is intended to characterize it as a fully planned and coherent system, rather than an incremental accretion of very specific and inflexible tools, as is frequently the case with other data analysis software.

<p align="justify">R, like S, is designed around a true computer language, and it allows users to add additional functionality by defining new functions. Much of the system is itself written in the R dialect of S, which makes it easy for users to follow the algorithmic choices made. For computationally-intensive tasks, C, C++ and Fortran code can be linked and called at run time. Advanced users can write C code to manipulate R objects directly.

<p align="justify">Many users think of R as a statistics system. We prefer to think of it of an environment within which statistical techniques are implemented. R can be extended (easily) via packages. There are about eight packages supplied with the R distribution and many more are available through the CRAN family of Internet sites covering a very wide range of modern statistics.

<p align="justify">R has its own LaTeX-like documentation format, which is used to supply comprehensive documentation, both on-line in a number of formats and in hardcopy.

**Citation**： [Official Website](https://www.r-project.org/)

### Design of the R System
<p align="justify">The primary R system is available from the [Comprehensive R Archive Network](https://cran.r-project.org/), also known as CRAN. CRAN also hosts many add-on packages that can be used to extend the functionality of R.

The R system is divided into 2 conceptual parts:

1. The “base” R system that you download from CRAN: [Linux](http://cran.r-project.org/bin/linux/) [Windows](https://cran.r-project.org/bin/windows/) [Mac](https://cran.r-project.org/bin/macosx/) [Source Code](http://cran.r-project.org/src/base/R-3/R-3.1.3.tar.gz)

2. Everything else.

R functionality is divided into a number of packages.

* The “base” R system contains, among other things, the `base` package which is required to run R and contains the most fundamental functions.

* The other packages contained in the “base” system include `utils`, `stats`, `datasets`, `graphics`, `grDevices`, `grid`, `methods`, `tools`, `parallel`, `compiler`, `splines`, `tcltk`, `stats4`.

* There are also “Recommended” packages: `boot`, `class`, `cluster`, `codetools`, `foreign`, `KernSmooth`, `lattice`, `mgcv`, `nlme`, `rpart`, `survival`, `MASS`, `spatial`, `nnet`, `Matrix`.

When you download a fresh installation of R from CRAN, you get all of the above, which represents a substantial amount of functionality. However, there are many other packages available:

* There are over 4000 packages on CRAN that have been developed by users and programmers around the world.

* There are also many packages associated with the [Bioconductor project](http://bioconductor.org/).

* People often make packages available on their personal websites; there is no reliable way to keep track of how many packages are available in this fashion.

* There are a number of packages being developed on repositories like GitHub and BitBucket but there is no reliable listing of all these packages.

### Limittations of R
<p align="justify">No programming language or statistical analysis system is perfect. R certainly has a number of drawbacks. For starters, R is essentially based on almost 50 year old technology, going back to the original S system developed at Bell Labs. There was originally little built in support for dynamic or 3-D graphics (but things have improved greatly since the “old days”).

<p align="justify">Another commonly cited limitation of R is that objects must generally be stored in physical memory. This is in part due to the scoping rules of the language, but R generally is more of a memory hog than other statistical packages. However, there have been a number of advancements to deal with this, both in the R core and also in a number of packages developed by contributors. Also, computing power and capacity has continued to grow over time and amount of physical memory that can be installed on even a consumer-level laptop is substantial. While we will likely never have enough physical memory on a computer to handle the increasingly large datasets that are being generated, the situation has gotten quite a bit easier over time.

<p align="justify">At a higher level one “limitation” of R is that its functionality is based on consumer demand and (voluntary) user contributions. If no one feels like implementing your favorite method, then it’s your job to implement it (or you need to pay someone to do it). The capabilities of the R system generally reflect the interests of the R user community. As the community has ballooned in size over the past 10 years, the capabilities have similarly increased. When I first started using R, there was very little in the way of functionality for the physical sciences (physics, astronomy, etc.). However, now some of those communities have adopted R and we are seeing more code being written for those kinds of applications.

### R Resources
## Official Manuals
As far as getting started with R by reading stuff, there is of course this book. Also, available from [CRAN](https://cran.r-project.org/) are

* [An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.html)

* [R Data Import/Export](https://cran.r-project.org/doc/manuals/r-release/R-data.html)

* [Writing R Extensions](https://cran.r-project.org/doc/manuals/r-release/R-exts.html): Discusses how to write and organize R packages

* [R Installation and Administration](https://cran.r-project.org/doc/manuals/r-release/R-admin.html): This is mostly for building R from the source code)

* [R Internals](https://cran.r-project.org/doc/manuals/r-release/R-ints.html): This manual describes the low level structure of R and is primarily for developers and R core members

* [R Language Definition](https://cran.r-project.org/doc/manuals/r-release/R-lang.html): This documents the R language and, again, is primarily for developers

## Other Resources
* Major technical publishers like Springer, Chapman & Hall/CRC have entire series of books dedicated to using R in various applications. For example, Springer has a series of books called Use R!.
* A longer list of books can be found on the [CRAN web site](https://www.r-project.org/doc/bib/R-books.html).

**Citation**： [R Programming for Data Science](https://bookdown.org/rdpeng/rprogdatascience/) Author: Roger D. Peng

[<div><i class="fa fa-hand-o-up fa-2x "></i>***Return top***</div>](#jump)


---