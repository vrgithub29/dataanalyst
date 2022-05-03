**Case Study: How Does a Bike-Share Navigate Speedy Success?**

Section 1: ASK
a, What is the problem you are trying to solve? The objective is to maximize the number of annual membership

Section 2: PREPARE
Picked up the data provided in the case study. Picked up 1 year data to analyse.

Section 3: PROCESS

I have used python as the programming language to clean the data. I have removed null values, converted objects to datetime and whereever possible filled gaps with mean values. 
Used basic libraray files to perform the exploratory data analysis. 
Calculated the ride length as given in the case study, calculated day of the week by using weekday functionality and replaced numbers with respective Weekday using Dictionary 
Added these new columns back to the dataframe.

Section 4: ANALYSIS
Calcualted mode, mean and maximum ride length for casual and membership riders . Based on this below are my findings 

mean ride or average ride length of casual riders was the highest
maximum ride length of casual riders was the highest
Casual riders tend to ride more on Friday whereas members ride more on tuesday


Section 5:- SHARE 
The number of riders for both member and casual are more or less the same 
The rider counts drops from the month of November until Feb after which it start picking up again 

Section 6:- ACT
1, Casual members tend to use more on Fridays. Reducing the price of bike on Fridays for members only mgiht tempt casual riders to become members
2, Bikes can be booked for members on Fridays but for casual members its First come first serve basis. This might tempt casual riders to become members



