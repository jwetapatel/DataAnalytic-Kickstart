# Kickstarter-analysis
## Overview of Project
We need to help Louise with her project campaign, and we'll be performing data analysis on several thousand crowdfunding projects to uncover any hidden trends. 

### Purpose of the project 
Louise’s play "Fever" came close to its fundraising goal in a short amount of time. With charts and graphs, we will analyze how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges 

### Theater outcome by Launch date

With the existing Kickstarter data, I started analyzing for Louise's crowdfunding campaign in excel. 
To reach to the conclusion first I filter the data based on parent categories and year.
Based on above filtering we analyze the theater outcomes by launch date (i.e., successful, failed or canceled). The graphical presentation is shown as below.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96400887/164874623-7cf876a8-1705-454d-9a6d-6dbc38c3a544.png)

Followed below steps to generate the filter pivot chart : 
 - Create a pivot table from the KickStarter worksheet, and place the pivot table in a new sheet.
- Label the sheet "Theater Outcomes by Launch Date."
- Filter the pivot table based on "Parent Category" and "Years."
- Place the appropriate pivot table fields in the columns, rows, and values.
- Filter the column labels to show only "successful," "failed," and "canceled."


### Outcome based on goals

Now with the kickstarter data I started analysis of "Outcomes Based on Goals." and as per given data created the following dollar-amount ranges so projects can be grouped based on their goal amount and 
Followed the below steps for above mention analysis:
- In the new sheet create the columns to held the data of goal, number of successful, failed, canceled campaign also total number of projects, then calculate the percentage of succsessful, failed, canceled data
- Use COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount, and on the "Subcategory" column using "plays" as the criteria.  
- Use the SUM() function to populate the "Total Projects" column for successful, failed, and canceled projects for each row.
- Calculate the percentage of successful, failed, and canceled projects for each row
- Created a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges and percentage of successful, failed, or canceled projects
Graphical presentation of "Outcomes based on Goals" is shown as below.
 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96400887/164874637-1a48f049-a2e8-4136-af3e-1389c1ba8cb6.png)
