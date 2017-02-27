# bcb bootcamp - R section
@laneharrison  
2/11/2017  

### 2/13/2017: Note- I have changed the exercises for the first week.
### 2/20/2017: Note- I have added exercises for the second week.

Welcome to the R section of your "bootcamp"!

R is a programming language geared towards statistical computing.

What makes R exciting is its community.
Research groups and statisticians regularly publish R packages that allow you to reproduce and extend their analyses.
R is an excellent choice for exploratory *and* confirmatory data analysis.

In this class we have three weeks together.
And while there is some flexibility in what we cover, most of our exercises will focus on a small set of learning goals.
Specifically, upon successful completion of this section, you should be able to:

1. Use R for routine analytical tasks: invoking stastical functions, loading data, producing documents / figures, installing packages, etc.
2. Visualize any given dataset in multiple ways, through a rudimentary understanding of the "Grammar of Graphics", and `ggplot2`.
3. Manipulate, arrange, and mutat datasets you encounter using `dplyr`.

This will provide you with a foundation for using R in your analysis workflow.

# Text

The book for this section is [R for Data Science](http://r4ds.had.co.nz/) (R4D) by [Hadley Wickham](http://twitter.com/hadleywickham).

Each week's learning activities will center around an assigned reading and exercises from R4D.

R4D is up-to-date, good, and free.
I recommend exploring this book well beyond the assigned exercises in this section.

# Assignments

To assess your progress, each week we'll assign a set of exercises from the R for Data Science book.

**Guidelines:** Some questions will require you to type out your reasoning or predictions. 
For example, question 5 in exercises 3.6.1 asks, "Will these two graphs look different? Why/why not?".
For these types of questions, provide text along with any code you used to help answer them.

To turn these in, simply output an R Markdown document to PDF and upload **both the PDF and your Rmd** to Canvas.

# In Class

I'll introduce each topic, but most in-class time will be dedicated to completing the assigned exercises and getting help where you need it.

# Week 1 - Getting Started & Data Visualization

In our first week, we'll become acquainted with R, R Studio, and learn to plot data we encounter with `ggplot2`.

## in-class discussion

- How WPI VIEW uses R + R Markdown for data visualization research.
- How your tools shape to you.
- Deliberate Practice (vs. Learning in The Trenches (vs. Shortcuts in the Trenches))
- Open Science: Challenges and Benefits

## reading

R for Data Science, Chapters 26-27.3, 1-3

## exercises

- 27.2.1 (10m)

- 3.2.4 (10m)
- 3.3.1 (15m)
- 3.5.1 (25m)

# Week 2 - Data Wrangling

[slides](week2-inclass.html)

This week we'll tackle data wrangling with `dplyr`, which will probably take up more of your time than actual statistics, modeling, and visualization!.

## in-class discussion

- Why data wrangling is so pervasive.
- Tidy data concepts
- `dplyr`, the tidy data tool

## reading

R for Data Science, Chapters 5. 
(If you want to really dive in, do 9-12, too.)

## exercises

- 5.5.2 question 1 (10m)
- 5.6.7 (30m)
- 5.7.1 (30m)

# Week 3 - Putting it Together

*TBA*

## The "Final" Project

Produce an original document with the following features:

- Use data from your own research or your labs research. 
    - (You may use data online, but only as a last resort.)
- (The Data) Describe the data in its original form. For example: How large is it? How many columns? How many rows? What types of columns? Is there missing data?
- (EDA) Conduct an exploratory analysis of the dataset. This should be your longest section. Include text, plots, tables, statistics, and possibly statistical tests.
- (Hypothesis) A brief section on some hypothesis you've generated about the data. Maybe you found something interesting in EDA that you would like to write up further, or you want to run statistical tests + charts to prove something. Sometimes you'll need to bring in additional data. This should be a result of your EDA.
- (Transformation) A brief section on the transformations you're making to the data to explore your hypothesis.
- (Results/Summary) Write up your results in a way that a newcomer can immediately grasp what was done, without any of the other sections as background. The visualizations you generate here should be well-designed and captioned such that they can exist on their own.

# Links

- [CRAN])(http://cran.r-project.org/)
- [yatani.jp: HCI experiment statistics w/ R examples](http://yatani.jp/teaching/doku.php?id=hcistats:start)
- [\@hrbrmstr's R Workshop WPI 2016](https://hrbrmstr.github.io/WPIRWorkshop/)

- [propr: An R-package for Identifying Proportionally Abundant Features Using Compositional Data Analysis](http://biorxiv.org/content/early/2017/02/01/104935)
