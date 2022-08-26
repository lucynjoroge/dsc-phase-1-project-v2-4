# Microsoft Movie Project
## Overview
Microsoft, An Americal multi-national company wishes to dive into movie Production. The task at hand is to conduct an analysis to better answer some of their business questions.
In this case, the analysis requires that I take a deep dive into the datasets given by looking at the certain factorss that I might use in the research as well as making sure that the data set is ready for use. 
In this analysis, I made use of the jupyter Notebook , Vs code, Github Desktop and several libraries and documentation to help enhance the credibility of my analysis.

## Business Understanding
The problem at hand is quite simple , recommend a good movie genre. The findings of my analysis can be beneficial to Microsoft or any company that wishes to indulge in movie production or any individual who wishes to conduct any research on the various genres as well as their performances with the audience. 
In this project , I have conducted research based on these leading questions:

a) Which movie genre has the highest ratings?

b)Which movie genre generated the highest gross profit  given the production budget?

c) Which movie genre generated the highest worldwide gross.


## Data Understanding and Analysis
### Source of Data
The dataset used in the analysis has been provided by Flatiron school and is from various reports from sites such as IMDB, The Numbers, Box Office Mojo , Rotten Tomatoes and The movie DB which all conduct research on movies to display various reviews as well as their performance. There are a total of 6 data sets  taking different file formats.

### Description of data
The dataset used in this particular analysis is the IMDB dataset and the Numbers. The IMDB dataset is in  an SQLIte database and has to be obtained by importing sqlite3 and connecting to the database.
There are only two tables in the database that will be in use and which will be merged with the Dataset from The Numbers to conduct the final analysis. The final dataframe has a total of 2875 rows and 14 columns.

### Data Preparation and  Cleaning
This will be a big part of the analysis and entails identifying and getting rid of missing values, null values, outliers, duplicates, outliers and extraneous values. Some methods used to check for missing values was the .isna() method , for duplicates ,.unique() and .describe() for outliers. The methods used for taking care of missing values were dropping rows and a single column and filtering out the duplicated values. Once cleaned, the final dataframe should have a total of 2126 rows and 13 columns

### Data Analysis
This revolves around plotting and making inferences as well as recommendations. The tools in use for this analysis are matplotlib, numpy and pandas. Plotting is  particular to the columns of interest and there is a number of groupings done per dataframe using the .groupby() method. This is because the nature of the analysis centres its focus on the genres and not individual movies. Plotting the dataframes correctly also includes labelling their axes and giving titles with the appropriate observation and recommendation inferred from these plots

### Visualizations
The visualizations that will be encountered and used in the analysis are the following bar graphs:

![alt text](https://github.com/lucynjoroge/dsc-phase-1-project-v2-4/blob/master/P.Analysis%20plots/Worldwide_gross%20Image.png?)
  
  This the bar plot showing the genres generating the highest worldwide gross

![alt text](https://github.com/lucynjoroge/dsc-phase-1-project-v2-4/blob/master/P.Analysis%20plots/gross_profit_df.png) 
   
   This is the bar plot showing the genres generating the highest gross profit.

![alt text](https://github.com/lucynjoroge/dsc-phase-1-project-v2-4/blob/master/P.Analysis%20plots/rate_df.png)
 
   This is the bar plot showing the genres with the highest average ratings

There are also scatter plots included which have been plotted using matplotlib to analyze the relationship between various variables in the dataframe
The most prevalent one however , used in the analysis is that of the production budget and gross profits used to test if there is any relationship between them.

![alt text](https://github.com/lucynjoroge/dsc-phase-1-project-v2-4/blob/master/P.Analysis%20plots/profit_and_budget_df.png)

From the scatter plot above, it can be concluded that the production budget and gross profits are closely related.

## Conclusion

There are various methods that have been used to conduct this analysis, including a t- test  to determine if the averageratings are biased. Correlation has also been in use, where visualizations and scatter plots have been used as well as the numpy correlation function.

There are three recommendations made as well as a definite conclusion as listed below:
a) The genre generating the highest worldwide gross is the Action , Adventure and Sci-Fi genre , which should be considered if worldwide gross income is in mind.
b)The genre generating the highest gross profit is the Action , Adventure and Sci-Fi genre , which should be considered if gross profit  is in mind having put into consideration the movie production budget.
c) The genre that has the highest average ratings is the Action.Documentary and Drama genre
#### Definite conclusion
To produce films that are making the highest worldwide gross and gross profits, the a high production_budget should also be expected.