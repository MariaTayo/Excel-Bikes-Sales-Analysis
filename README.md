# Excel-Bike-Sales-Analysis


## Background 
This project was part of an analysis of purchased bike sales using Microsoft Excel. The dataset included details about customers' demographics including marital status, gender, education and occupation and also whether they purchased a bike or not. This was part of a project by Alex the Analyst. 

## Data Cleaning
Cleaning steps taken were as follows: 
* Checked to see whether there were any duplicates in the dataset. There were no duplicates to be removed in the dataset.
* Reviewed each column. Replaced the marital status input from "M" and "S" to "Married" and "Single" using find and replace. Also replaced gender input from "M" to "Male" and "F" to "Female".
* Changed the format for the income column to currency and removed additional zeros.
* Created a new column for age and used the IF formula (nested if statement) to seperate the different age and ranges to new categories (Young Adult, Middle Aged and Old). 

## Data Analysis
Before conducting analysis, I created a pivot table. 
* I then looked at the average income of someone who purchased a bike vs someone who did not purchase a bike. The average income per purchase was higher for men than it was for females. The average income of men who had purchased a bike was $60,124 compared to that of females which was $55,774. The average income of those who did not purchase a bike was $53,440 for females and $56,208 for men. 
* I then looked at the customer commute distance based on whether the customer purchased a bike or not. The question is to determine whether commute distance makes a difference to the bike purchases being made. 
* I looked at the customer age and those who purchased a bike vs those who did not. This was done based on the age category brackets created. People under the age of 30 (young adults) are not purchasing as many bikes. The majority of bike purchases were made from customers in the middle age bracket (those aged 31-54). It was also clear that the majority of customers are from the middle age range which was useful insight which could help with any marketing initiatives. 
* Lastly, I analysed purchases made within each region and discovered that the majority of bike purchases (508) were made in North America.
* Pivot Graphs were then created based on the results of the analysis.

## Visualisations and Dashboard
The visuals (pivot graphs) created from my analysis were used to create a dashboard with slicers in order to incorporate filters. One of the filters included marital status. This highlighted some interesting insights in terms of purchases by single customers vs customers that are married, their average income, age brackets and commute. A filter was also included based on educational status.  

![_Bike Sales Dashboard](https://github.com/MariaTayo/Excel-Bikes-Sales-Analysis/assets/117232459/8f60fa00-992c-400c-855b-f7539b940fb3)

## Findings
* The average income per purchase was higher for men than it was for females.
* The majority of bike purchases were made from customers in the middle age bracket (those aged 31-54).
* The majority of bike purchases (508) were made in North America.


