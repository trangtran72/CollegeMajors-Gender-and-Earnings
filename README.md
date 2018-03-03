## CollegeMajors-Gender-and-Earnings

This repository contains information on the analysis about the effect of women's representation and college majors, on the average median incomes

This project is an extension to the project done by *FiveThirtyEight*. 

The [link](https://github.com/fivethirtyeight/data/tree/master/college-majors) to their repository

The result of their project was published as [an article](https://fivethirtyeight.com/features/the-economic-guide-to-picking-a-college-major/) *The Economic Guide To Picking A College Major* on their website in 2014. 

In this project, I will be using the cleaned dataset from *FiveThirtyEight*. However, instead of producing visualizations and tables as what they did for the article, I will be looking for a model, that can some how explains the median income. Additionally, I will create new variable(s) for my model.

**Original Data**

The original dataset is from American Community Survey 2010-2012 Public Use Microdata Series.

[Link](http://www.census.gov/programs-surveys/acs/data/pums.html) to the original ACS data

[Link](http://www.census.gov/programs-surveys/acs/technical-documentation/pums.html) to the documentation

**Cleaned dataset**

`all-ages.csv`
This [file](https://github.com/fivethirtyeight/data/blob/master/college-majors/all-ages.csv) contains the first cleaned dataset from FiveThirtyEight

`women-stem.csv`
This [file](https://github.com/fivethirtyeight/data/blob/master/college-majors/women-stem.csv) contains the second cleaned dataset from FiveThirtyEight. *ShareOfWomen* was added


`salary_edited.csv` My version of the data, combined from all-ages.csv and  . Added a new variable called *Engineering*, which takes value 1 if the major falls under category *Engineering*, and 0 otherwise.

**Result**

`Test College GPA.Rmd` The R script that I created to build and test my model of interest

`Predictive Modelling.pptx` This file contains the results of the project, and its supported visualizations. The result was given in a presentation for MATH 215 at Denison University
