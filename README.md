![HotCars-Head](pics/HotCars-head.png)

##Question 1: Which line has the most critical hot car issue during sepecific day?
They use a heatmap with weekdays as rows and Line Labels as column. The redder, the higher possibilities of taking a hot car. if color of two rectangles are similar, user can check actual possibilities in linearGradient.

![HotCars-Q1](pics/HotCars-Q1-2.png)

##Question 2: I want to check the frenquencies and ratios of each car type.
In parallel coordinates chart, they visualized "Hot Car" frequency count within 5 years (shown in the axes from "Year:2010" to "Year":2014). They calculated the ratios by using count divided by its "TotalNumber". "AvgMRatio" stands for average ratio for each car type in a certain month within 5 years. "AvgRatio" is the average AvgMRatio within all these months. By using brush to select lines in the chart below, you can either check the frenquencies and ratios of each car type, or view the trend in a certain month.
![HotCars-Q2](pics/HotCars-Q2-2.png)

##Question 3: What is the ratio of repairing method for specific years aged cars for specific damage type?
In the sunburst chart, the inner ring represents different in-service age groups, the middle ring is the manufactuer, the outer ring shows car type.
And the parallel set shows the relationship between reasons of the hot car problems(dirty, leaking, H/W damaged, malfunctioning, others), repairing method(reset, repair, replace) and "Hot Car" frequency trend.
![HotCars-Q3](pics/HotCars-Q3.png)
===
#####Project Link: http://hotcars-nyc.github.io/
