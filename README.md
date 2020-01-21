A Practical Introduction to Data Visualization with ggplot2
================

### rstudio::conf 2020

by Kieran Healy

-----

:spiral_calendar: January 27 and 28, 2020  
:alarm_clock:     09:00 - 17:00  
:hotel:           Golden Gate Rooms 6-7 (Lobby Level)  
:writing_hand:    [rstd.io/conf20-dataviz](http://rstd.io/conf20-dataviz)

-----

## Overview

This course will teach you how to think about good data visualization, and how to do it. We begin with some core principles about how we see graphs, what makes some of them better than others, and how to begin cultivating good judgment about visualization. Then, through a series of worked examples, you will learn how to use ggplot to make graphs piece by piece. The emphasis throughout is on acquiring a practical feel for and good judgement about the way ggplot can be used, from the simplest cases to sophisticated, highly customized data visualizations.  

The effective use of graphs and charts is an important way to explore data for yourself and to communicate your ideas and results to others. Being able to produce effective plots from data is also the best way to develop an eye for reading and critically understanding visualizations made by others, whether presented in academia, business, policy, or the media. Learning how to visualize data effectively is more than just knowing how to write code that produces figures from data. This course will teach you how to do that. But it will also teach you how to think about the information you want to show, and how best to present it to your audience—including when the audience is yourself.

## Learning objectives

ADD LEARNING OBJECTIVE(S)

## Is this course for me?

You should take this workshop if:

1. You want to understand the basic principles behind effective data visualizations, and how they are implemented in R and ggplot.
2. You want to better develop your practical sense for why some graphs and figures work well while others do not.
3. You want to feel more confident and fluent in ggplot, in order to make, refine, and effectively present good data visualizations.



## Prework

We will be working with the most recent stable versions of R and RStudio, as well as with a number of additional packages. You can either install R, RStudio, and the necessary packages locally, on your own laptop, or use an RStudio Cloud workspace in your browser.

### Running R and RStudio on your Laptop

- If you are running the software locally on your laptop, begin by installing R (<http://cloud.r-project.org>) and RStudio (<http://rstudio.com>). 
- Once the applications are installed, launch RStudio. Either type or copy and paste the following lines of code at R’s command prompt, located in the RStudio window named “Console”, and then hit return. In the code below, the <- arrow is made up of two keystrokes, first < and then the short dash or minus symbol, -.

``` r
my_packages <- c("tidyverse", "broom", "coefplot", "cowplot", "drat",
                 "gapminder", "GGally", "ggforce", "ggraph", "ggrepel", "ggridges",  
                 "graphlayouts", "gridExtra", "here", "interplot", "margins", 
                 "maps", "mapproj", "mapdata", "MASS", "naniar", "prismatic", 
                 "quantreg", "rlang", "scales", "socviz", "survey", "srvyr", 
                 "viridis", "viridisLite", "devtools")

install.packages(my_packages, repos = "http://cran.rstudio.com")

```

If you do not have one already, it will be useful to create a GitHub account and obtain a GitHub Personal Access Token. Read and carefully follow the instructions in Parts I and II of [Happy Git With R](https://happygitwithr.com), and then also the instructions in [Appendix B](https://happygitwithr.com/github-pat.html) of the same document.

### Running R from RStudio.cloud, via your Web Browser

[Instructions to follow]


## Schedule

### Day 1

| Time          | Activity               |
| :------------ | :---------------       |
| 09:00 - 10:30 | Looking at data        |
| 10:30 - 11:00 | *Coffee break*         |
| 11:00 - 12:30 | Make some plots        |
| 12:30 - 13:30 | *Lunch break*          |
| 13:30 - 15:00 | Show the right numbers |
| 15:00 - 15:30 | *Coffee break*         |
| 15:30 - 17:00 | Working with Geoms     |

### Day 2

| Time          | Activity           |
| :------------ | :---------------   |
| 09:00 - 10:30 | Plots from Models  |
| 10:30 - 11:00 | *Coffee break*     |
| 11:00 - 12:30 | Making Maps        |
| 12:30 - 13:30 | *Lunch break*      |
| 13:30 - 15:00 | Polishing Plots    |
| 15:00 - 15:30 | *Coffee break*     |
| 15:30 - 17:00 | ggplot in Practice |


## Instructor

[Kieran Healy](https://kieranhealy.org) is Professor of Sociology at Duke University. He is the author of [Data Visualization: A Practical Introduction](http://socviz.co) (Princeton University Press, 2019). Much of his research has been about the social organization of exchange in human blood and organs, cultural goods, software, and ideas. His current work focuses on the moral order of market society, the effect of models and measurement on social classification, and the link between those two topics, especially in the consumer credit market. You can learn more at [https://kieranhealy.org](https://kieranhealy.org)

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
