# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to:
1. Find out the trend for the main *Theatre* category based on its launch date.
2. Understand the behaviour of the subcategory *Plays* based on its funding goal.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Dated
1. To analyze the outcomes based on the launch date we need a pivot table which mainly focuses on the number of successful, failed and 
   canceled projects launched throughtout the year. 
2. As we are mainly interested to see the trend for the *theatre* category we need to filter our data inside the pivot table 
   based on the *theatre* category. 
3. Now we have a pivot table consisting of count of successful, failed and canceled campaigns in all the 12 months for all the years
   from *2009* to *2017*.
4. By filtering more into the year, we can see that in the year of *2015*, the number of successful theatre campaigns were the highest(314).
5. We use line chart(below) to represent relation between number of different kind of outcomes for the projects based on the launch date. 
![](./Resources/Theater_Outcomes_vs_Launch.png)
   - Over the period of 9 years, highest number(8%)of projects which were successful launched during the month of May. Lowest number(3%) of
  successful projects were launched during the month of December. 
   - Number of projects which failed were almost constant for all the months ranging from 3-4%. 
   - Only 0.2% of the projects launched got canceled throughtout the year. 
   - Projects which were successful are almost double the amount of projects which were failed. 


### Analysis of Outcomes Based on Goals
1. To analyze the outcomes of the projects based on the goal amount we need a pivot table with different goal amounts 
   and the corresponding number of projects which were successful, failed and canceled. 
2. As the goal amount ranges from 1000 to 50k, it is good to create slab/intervals of amount. 
3. Looking at the data, 
   - 
   - 
  

### Challenges and Difficulties Encountered
- As the unit for launch date was in unix timestamp, there was an extra step included to convert the time into date format. 
  Moreover to split out the years from the date, we had to perform one more step to extract year using the inbuild excel function
  **=YEAR()**
- For the "Outcomes based on Goals" data, as the goal amount ranged from 1000 to 50k, we had to create the slab/Intervals
  of amounts to analyze the data more properly. 



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The highest number of projects which got successful for the Theatre category were launched in the month of May. It drastically dropped
     from 111 to 35 during the second half of the year. 
  2. Number of projects which failed were almost constant in the range of 30-40 during the entire span of the year whereas projects which 
     got canceled were very few ~4-7 from Jan to dec.  

- What can you conclude about the Outcomes based on Goals?
  1. The percentage of projects whch were successful,were inversely propotional to the goal amount, 
     on the contrary percentage of projects which were failed were directly propotional
     the number of projects which failed kept on increasing. 
	 

- What are some limitations of this dataset?
  1. This data set lacks the subcategory which would help us to see which entry from the main Theatre category was launched 
  2. Having the pledge amount apart from goal amount would have helped to understand the percentage of successful and failed projects
     more accurately. 

- What are some other possible tables and/or graphs that we could create?
  1. 
