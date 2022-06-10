# Pandas-Challenge
Homework 4 - Pandas Northwestern University Boot Camp

For this challenge, we were asked to create 8 data frames which displayed a:

* District Summary
* School Summary
* The 5 Highest Performing Schools
* The 5 Worst Performing Schools
* Math Scores By Grade
* Reading Scores By Grade
* Scores By School Spending
* Scores By School Size
* Scores By School Type

It was a daunting challenge, but enjoyable nonetheless! My single file of code successfully read through 2 spreadsheets provided and was also able to provide the 8 data frames with their corresponding calculations. 

While looking at the results of my console, it seems that there is likely not much correlation with school budgets and resulting scores. I observed that the top and bottom performing schools had a very different set of budgets, so it is not possible to conclude that budget has anything to do with increased performance.

However, when looking at the DataFrame showing the budget per student as well as the one by school size, both tend to show higher scores the lower the size and budget. This is a very shallow overview of the DataFrame as I didn't draw any statistical calculations, such as r values, that could tell more about the correlation between scores, size, and per student budget.

Lastly, when looking at the DataFrame showing the school types and scores, it is evident that there is a disparaging difference in scores between those schools that are Charter Schools, and those that are District Schools. This is mainly noted in the percentage passing scores for reading, math, and especially those of the overall passing scores. In this instance, there was an almost 40% difference between the overall passing scores between the two school types, Charter Schools with the higher score at ~90%. From the observations I was able to make between the different DataFrames, the biggest difference by far of scores was between school types, so it's possible the way Charter Schools vs District Schools function may be having a positive impact on student performance. But I cannot assume anything without further calculations.
