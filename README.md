# pandas-challenge
Module 4 - Pandas Challenge
## Before Beginning
Before shaping, cleaning up and reviewing the information, the jupyter notebok PyCitySchools imported Pandas, read the 2 CSV files from /Resources, and then merged them together. This provided me with a comprehensive data set for the necessary review.

## District Summary
Once combined, I used the set to calculate the total number of unique schools, total number of students, total budget, mean math score, mean reading score, percentage of students passing math, percentage of student passing reading and percentage of students passing both. These values were then stored in a new data frame. This allows us to view the district's overall performance, as well as provides a baseline to compare individual schools against.

## School Summary
Then, I made a new section based on selecting the school type, and calculated the same metrics as in the "District Summary" section. They were then stored in a dataframe, so that the school specific rates were visible, to provide a more granular view. With this and the "District Summary", we have the information to check how individual schools are performing compared to the district's average performance.

## Summary Calculations
With the information provided by the above dataframe, I created new dataframes to sort and present the school data by:
  * Highest performing schools (by percentage passing both math and reading)
  * Lowest performing schools (by percentage passing both math and reading)
  * Math scores by grade for each school
  * Reading scores by grade for each school
  * Math and Reading scores by amount spent per student (shown in groups of spending ranges)
  * Math and Reading scores by total student population (shown in groups of student population totals)
  * Math and Reading scores by school type (grouped by the labels "Charter" or "District")
