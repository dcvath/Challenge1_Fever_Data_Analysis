# Kickstarting with Excel

## Overview of Project
This is an analysis to provide Louise with additional information regarding fundraising for her play, Fever. The fundraising is approaching its goal in a relatively short period of time. Due to this fact, Louise requested an analysis of how different campaigns fared in relation to their launch dates and their funding goals.

### Purpose
Visualize campaign outcomes based on their launch dates and their funding goals to give Louisa an idea of where her fundraising campaign might finish.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the Outcomes Based on Launch Data analysis, I used the "Years()" function to add the year that each campaign launched. Then, I created a pivot table from the data in the Kickstarter tab. I filtered the data by "Parent Category" and "Years", added "Outcomes" as a column, "Data Ended Conversion" as a row, and "Outcomes" as a value. I filtered the column labels to only show "successful," "failed," and "canceled" and filtered "Parent Category" to only show the data for "theater."

Next, I created a line chart from the pivot table and added a title to the chart and saved it as an image. Please see a screen shot of this line chart below. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85654649/124370197-9b83f200-dc42-11eb-9e9a-722d86188c94.png)



### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

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
