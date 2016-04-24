# Atus-Analysis

##Analyzing U.S. Department of Labor's data on Americans' time use

[Link to Jupyter Notebook](https://github.com/conleydg/atus-analysis/blob/master/wasting_time.ipynb)

I used three different CSV files from the US. Department of Labor for this project. The files contain information from surveys that were conducted to find out how Americans spend their free time. I am going to use this information to see if there are any meaningful correlations between things like income, region, time spent with family, and number of people in the household.

The first portion of the Jupyter Notebook reads in data from three different CSV files from the US. Department of Labor. The files contain information about income, demographics, and how each person spends their time. The files are then turned into three separate dataframes. The three dataframes are then merged into one dataframe based on the column's ID number.

I then create three new dataframes in order to compute correlations. They are grouped by Region, Family Income, and Activity Code. The Jupyter Notebook contains graphs that shows the relationships and correlations.

### Takeaways

The strongest correlation coefficient I found was .25, which was between family income and number of people in household.

There is also a slight relationship between income and how a persons time is spent. The more money a person earns, the less alone time they have but they have more time with family than someone who earns less.

