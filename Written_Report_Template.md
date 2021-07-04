# Kickstarting with Excel

## Overview of Project
This is an analysis to provide Louise with additional information regarding fundraising for her play, Fever. The fundraising is approaching its goal in a relatively short period of time. Due to this fact, Louise requested an analysis of how different campaigns fared in relation to their launch dates and their funding goals.

### Purpose
Visualize campaign outcomes based on their launch dates and their funding goals to give Louisa an idea of where her fundraising campaign might finish.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the Analysis of Outcomes Based on Launch Date, I used the "Years()" function to add the year that each campaign launched to the "Kickstarter" sheet. Then, I created a new sheet with a pivot table from the data in the Kickstarter tab. I filtered the data by "Parent Category" and "Years", added "Outcomes" as a column, "Data Ended Conversion" as a row, and "Outcomes" as a value. I filtered the column labels to only show "successful," "failed," and "canceled" and filtered "Parent Category" to only show the data for "theater."

Next, I created a line chart from the pivot table and added a title to the chart and saved it as an image. Please see a screen shot of this line chart below. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85654649/124370197-9b83f200-dc42-11eb-9e9a-722d86188c94.png)


### Analysis of Outcomes Based on Goals
For the Analysis of Outcomes Based on Goals, I created a sheet titled, "Outcomes Based on Goals." Within this sheet, I created the following columns:
- Goal
- Number Successful
- Number Failed
- Number Canceled
- Total Projects
- Percentage Successful
- Percentage Failed
- Percentage Canceled

In the "Goal" column, I listed out the dollar-amount ranges for the goal amounts. Then, I used the "COUNTIFS()" function on the "Number Successful," "Number Failed," and "Number Canceled" columns. I filtered these columns accordingly. I used the "SUM()" function to fill-in the "Total Projects" column. I calculated the the percentage of "successful," "failed," and "canceled" projects by using a function to divide the respective outcome by the total projects. 

Next, I created a pivot table using the sheet I created. Then, I created a line chart of that pivot table and added the title, "Outcomes Based on Goal" to the chart. Please see a screen shot of this line chart below. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85654649/124370487-6bd6e900-dc46-11eb-84ff-dac785d34c2d.png)


### Challenges and Difficulties Encountered
On the Analysis of Outcomes Based on Launch Data, I ran into an error when I tried to use the "Years()" function, but I did some research on Google and found the error I made. It took a while for me to figure out how to just show the months in the pivot table, but after troubleshooting by removing and adding different pieces from "Filters" field, I figured it out. 

For the Analysis of Outcomes Based on Goals, it took me a while to figure out the "COUNTIFS()" function. After I figured out how the formula should display, then I worked on copying the formula across the difference outcomes, but this was taking a very long time because the formulas were not pasting appropriately. After using Google, I found that if I put dollar signs in front of the range letters, my formula would paste correctly. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1) Theater campaigns were most successful when launched in July becasue the campaigns launched in July had the highest success number. 
  2) Theater campaigns were least successful when launched in August becasue the campaigns launched in August had the highest failure number.

- What can you conclude about the Outcomes based on Goals?

Campaigns were most successful when the goal was less than $1,000. The percentage successful for campaigns that were leass than $1000 is 71%. In contrast, campaigns with a goal from $1,000 - $4,999 had noticeably higher failed rates.

- What are some limitations of this dataset?

This dataset does not include data about how much advertising was done for each of the campaigns. If we had this information, it may correlate to the success and failure of the campaigns. In addition, it does not breakdown the characteristics of the backers who pledged in the successful, failed, and canceled campaigns. If the dataset included this information, the data couuld be analyzed to determine what type of backers Louise should seek for her fundraising campaign.

- What are some other possible tables and/or graphs that we could create?
  1) Graph to show the average donation for the successful, failed, and canceled campaigns and their corresponding launch dates.
  2) Table and graph to analyze whether being a "staff pick" had any bearing on a higher successful rate of the campaigns and the corresponding launch dates and goals.
  3) Table to analyze which country had the most successful campaigns based on their launch dates and their fundraising goals.
