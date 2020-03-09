# Introduction to Econometrics

### Introduction to this repository

I have created this repository to summarize the key readings and information for an Econometrics course from my point of view.
Please let me know if you have any suggestions for improvement.

Below I listed a variety of readings with regard to Linear Algebra, Statistics, Programming and of course Econometrics.
In Addition to that there are some [Datasets](https://github.com/jonas7654/Econometrics/tree/master/Datasets
) stored in this repository for practice purposes.

---
### Introduction to Linear Algebra

* [MIT 18.06 by Gilbert Strang](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/) 

* [Gilbert Strang - Introduction to Linear Algebra (2016, Wellesley-Cambridge Press)](https://github.com/ParikhKadam/Introduction-to-Linear-Algebra-5th-Edition---EE16A/raw/master/Ed%205%2C%20Gilbert%20Strang%20-%20Introduction%20to%20Linear%20Algebra%20(2016%2C%20Wellesley-Cambridge%20Press).pdf) corresponding book to MIT 18.06

* [Essence of Linear Algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) by 3Blue1Brown, for a more intuitive approach to Linear Algebra

Some Additional reading:

- [Linear Algebra](https://web.calpoly.edu/~jborzell/Courses/Year%2010-11/Fall%202010/Petersen-Linear_Algebra-Math_306.pdf) by Peter Petersen - Chapters 1, 2.

- [Linear Algebra](http://joshua.smcvt.edu/linearalgebra/#current_version) by Jim Hefferon.

- [Linear Algebra Done Wrong](https://www.math.brown.edu/~treil/papers/LADW/LADW_2017-09-04.pdf)

- [Immersive Linear Algebra](http://immersivemath.com/ila/index.html), *an interactive web-book entirely on linear algebra.
 
- [Mathematics for Economists](https://primo.bib.uni-mannheim.de/permalink/f/19ojnqi/MAN_ALMA21119931390002561) - This Book is an essential Book for Economists and covers some basic Linear Algebra.
---
### Statistics
for some introduction to Statistics, Probability and Asymptotics
* [Bruce E. Hansen : Introduction to Econometrics (2020)](https://github.com/jonas7654/Econometrics/blob/master/pdf/Probability.pdf) 

* [jbstatistics](https://www.youtube.com/user/jbstatistics) is a series of videos for an intuitive introduction to Statistics by  [Jeremy Balka](https://mathstat.uoguelph.ca/people/balka)

---
### Econometric Readings
* [Bruce E. Hansen : Econometrics (2020)](https://github.com/jonas7654/Econometrics/blob/master/pdf/Econometrics.pdf)

* [Stock & Watson : Introduction to econometrics (2020)](https://primo-49man.hosted.exlibrisgroup.com/primo-explore/fulldisplay?docid=MAN_ALMA21219219330002561&context=L&vid=MAN_UB&lang=de_DE&search_scope=MAN_ALMA&adaptor=Local%20Search%20Engine&isFrbr=true&tab=default_tab&query=any,contains,Stock%20and%20Watson%202020&sortby=date&facet=frbrgroupid,include,140512103&mode=Basic&offset=0=)

* [Ben Lambert's](https://www.youtube.com/user/SpartacanUsuals/featured) video series on econometrics for undergradute and graduate students
---
### Measury Theory
**measury theory** is important and very helpful when trying to understand most statistical results

- [Understanding Analysis](http://cms.dm.uba.ar/academico/materias/verano2012/taller_de_calculo_avanzado/Libros/Abbott%20-%20Understanding%20Analysis.pdf) by Stephen Abbott - Chapters 6, 7, 

- [Principles of Mathematical Analysis](https://notendur.hi.is/vae11/%C3%9Eekking/principles_of_mathematical_analysis_walter_rudin.pdf) by Walter Rudin - Chapters 6, 11.

- [An introduction to measure theory](https://terrytao.files.wordpress.com/2011/01/measure-book1.pdf) by Terence Tao.

- [A Crash Course on the Lebesgue Integral and Measure Theory](https://www.gold-saucer.org/math/lebesgue/lebesgue.pdf)

---
### Software
To apply the models discussed in your Econometrics course we usually use Software. I will list some of the common used Software in Econometrics below.

**Open Source Software**
 - [R](https://www.r-project.org/) is a free software environment for statistical computing and graphics. [recommended reading](https://r4ds.had.co.nz/index.html).
 
 - [RStudio](https://rstudio.com/) is an integrated development environment for R. I recommend to use RStudio since it has a                        great GUI and additional tools e.g. for an easier package management. An introduction to Econometrics in R is given [here](https://github.com/jonas7654/Econometrics/blob/master/pdf/Econometrics_in_R.pdf)
 
 - [Julia](https://julialang.org/) is a relatively new **high performance** programming Language. It is a gerneral purpose language aiming for easy useage and high performance. Consider [Atom](https://atom.io/) as an IDE. An introduction to Econometrics in Julia is given [here](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf).
 
 - [Python](https://www.python.org/) is also a general purpose language widespread under scientists from all disciplines. An introduction to Econometrics in Python is given [here](https://pyecon.org/down/pyecon.pdf).
 
**Proprietary Software**
 - [STATA](https://www.stata.com/) is a general-purpose statistical software package. Many economists use STATA. An introduction to econometrics in STATA is given [here](https://github.com/jonas7654/Econometrics/blob/master/pdf/using_stata_for_principles_of_econometrics.pdf).
 
 - [MATLAB](https://www.mathworks.com/products/matlab.html) (matrix laboratory) is a multi-paradigm numerical computing  environment programming language. An introduction to Econometrics in MATLAB is given [here](https://www.mathworks.com/help/econ/).
 
 
 **List of Packages for [R](https://www.r-project.org/) , [Julia](https://julialang.org/) , [Python](https://www.python.org/) and [MATLAB](https://www.mathworks.com/products/matlab.html) to begin with**


The **[R](https://www.r-project.org/)** base Package contains all important packages for your model estimations. However sometimes there are packages who are better and easier to use in comparison to the base packages. I will list a few useful packages below.
 
 * [Tidyverse](https://www.tidyverse.org/) offers a variety of packages for data manipulation, plotting and importing. 
 
 * [sandwich](https://cran.r-project.org/web/packages/sandwich/index.html) for heteroskedastic variance estimation and more. See [here](https://cran.r-project.org/web/packages/sandwich/sandwich.pdf) for more information.
 
**[Julia](https://julialang.org/)** is not a statistical programming language in generel. But there are some useful Statistics packages.

  * [StatsBase.jl](https://docs.julialang.org/en/v1/stdlib/Statistics/) for basic statistics functionality.
  
  * [Distributions.jl](https://github.com/JuliaStats/Distributions.jl) A Julia package for probability distributions and associated functions.
  
  * [GLM.jl](https://juliastats.org/GLM.jl/stable/manual/) Linear and generalized linear models in Julia.
  
  * [Microeconometrics.jl](https://lbittarello.github.io/Microeconometrics.jl/stable/getting_started/) support for microeconometric estimation.
  
  * [GARCH.jl](https://github.com/AndreyKolev/GARCH.jl) Generalized Autoregressive Conditional Heteroskedastic for Julia.
  
  * [TimeSeries.jl](https://juliastats.org/TimeSeries.jl/latest/) package provides convenient methods for working with time series data in Julia. 

 **[Python](https://www.python.org/)** is not a statistical programming language in generel either. But there are some useful Statistics packages.
 * [NumPy](https://numpy.org/) is the fundamental package for scientific computing with Python.
 
 * [Pandas](https://pandas.pydata.org/) is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool.
 
 * [Matplotlib](https://matplotlib.org/) is a comprehensive library for creating static, animated, and interactive visualizations in Python.
 
 **[MATLAB](https://www.mathworks.com/products/matlab.html)** comes with it's own Econometrics Toolbox™
 
 * [Econometrics Toolbox™](https://www.mathworks.com/products/econometrics.html) provides functions for modeling economic data.
