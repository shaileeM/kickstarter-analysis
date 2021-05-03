# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to:
1. Find out the trend for the main *Theatre* category based on its launch date.
2. Understand the behaviour of the subcategory *Plays* based on its funding goal.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Dated
1. Part 1 of the analysis is mainly talking about trend based on the launch date for the Theatre category.
   To do so we need a pivot table which would mainly focus on the outcome of the entries present inside Theatre and the date
   on which it was launched. As year is one of the entity of the date, we extracted *year* from the launch date conversion using the 
   inbuilt excel function **=YEAR()**
2. We created a pivot table mainly consisting of the outcomes and year extracted in the step 1. 
3. As the purpose is to analize trend based on category and launch date we need 2 filters. 
   - Years 
   - Parent Category
4. The columns for the pivot table is the list of outcomes : successful, failed, canceled, grand total. 
5. The rows for the pivot table are the 12 months of the year. 
6. We are mainly interested to see the trend for the *theatre* category so we apply the filter on the parent category which 
   will only show theatre. 
7. Now we have a pivot table consisting of count of successful, failed and canceled campaigns in all the 12 months for all the years
   from *2009* to *2017*.
8. By filtering more into the year, we can see that in the year of *2015*, the number of successful theatre campaigns were the highest(314).
9. Visualization always helps more to find the trend from the gathered data. 
10.We use line chart(below) to represent relation between number of different kind of outcomes and its launch date. 
![](./Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
