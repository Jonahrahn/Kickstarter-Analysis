# Kickstarting with Excel

## Overview of Project
The Kickstarter project is used to demonstrate multiple functions in excel and their applications in the analysis of Data. In this project, I use functions to retrieve, analyze, and present data for different needs in the dataset. To interpret the data more effectively and towards a goal, I split the data up to filter out specific categories and subcategories of Kickstarter campaigns. This allows for more specific introspection into the research that can help others achieve funding for campaigns.

### Purpose
The purpose of this project was to take a set of Kickstarters Data and turn it into a descriptive analysis of how successful projects achieved their funding. While sorting through the data, I modified the data from 2009-2017 to fill any gaps to make the functions apply over the 85,000 data points in the main worksheet. After cleaning up the data, I visualized campaign outcomes based on their launch dates and their funding goals to better illustrate the best methods to achieve successful funding.

## Analysis and Challenges


![image_name](Chart%20of%20Outcomes%20based%20on%20Launch%20Date.png)


### Analysis of Outcomes Based on Launch Date
This graph was made using a pivot table to show the most effective time to launch a Theater Campaign. When looking at the graph of Outcomes-based on Launch date, the successful campaigns start strong in May with the highest level and slowly tapers off as the month's approach August.


![image_name](Chart%20of%20Parent%20Category%20Outcomes.png)


### Analysis of Outcomes Based on Goals
The idea for this graph was to represent the correct amount of money to set a campaign goal to achieve maximum success. To create this graph I used the CountIFs() function to separate the successful, failed, and canceled campaigns from each other.

### Challenges and Difficulties Encountered
+ Some challenges I encountered during this project were the number of unnecessary errors I made in manipulating the data beyond usability. I messed up some of the numbers by sorting and filtering the data. I went back in my past steps to see when I made the mistake and ended up resetting a portion of the datasheet to bring it back to usability.

## Results

- Conclusions about the Outcomes-based on Launch Date
+  This shows that the summer months have the highest success rate. On the other side, we can look at the amount of failed projects and how there is not too much of a conclusion to draw about specific months to avoid. When we look at the Successful and Failed campaign lines we see that December has almost the same amount for both Outcomes. The main conclusion is to aim for a summer launch and avoid the winter months especially December.

- Conclusions about the Outcomes-based on Goals
+ The Graph shows an inverse relationship between the Successful and Failed Campaigns. Starting from the lower funding goals, we see that the majority of campaigns are successful for the first four price ranges. This makes sense that the majority of the lower funding goals are met until the 15000-19999 range where the amount is equal for both of the outcomes. For the next three ranges, you can see the majority of campaigns fail until the 35000-39999 range. There is a window of success from 35000-44999 where more than 2/3 of the campaigns are meeting their goals. 45,000 and up is not the funding goal to be asking for as a hefty 15/17 are not meeting their funding goals. In Conclusion, this graph shows that if you are trying to have a successful goal met, your best luck is to avoid the 20000-35000 range and to not ask for more than 45,000.   

- Limitations of the dataset
+ The project has limiting factors that this dataset cannot address; limited years, other forms of marketing/advertising, and the extent of planning dedicated to the campaign. The years 2009-2017 are used for the dataset, which does miss a large portion of the recent campaigns for Kickstarter. The dataset used only provided blurbs and other forms of statistics, which leaves a question about the extent to which they used other forms of directing traffic towards their campaigns. The data is boiled down to simple data points which do not accurately demonstrate the amount of work that each of the people/team has put into the product behind the campaign.

- Possible tables and/or graphs that could be created later
+ Some possible Tables that I feel could show some interesting conclusions would be to use the Staff-pick and Spotlight data column to show the success rate of having either of those platforms for the campaign. The other categories in the worksheet that would help provide graphs of note would be the average donation and the number of backers. These could show a correlation between the amount of support that is required to be successful at the different funding ranges.

THANKS SO MUCH FOR READING! I HOPE YOU LEARNED SOMETHING!
