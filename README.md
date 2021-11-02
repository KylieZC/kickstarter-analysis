# kickstarter-analysis


## Overview of Project
Louise is a playwright who wants to raise more than $ 10,000 funds the budget for her play, Fever. And she seeks whether there are specific factors to promote the success of the fundraising. 

### Purpose
The project helps Louise uncover the facts and possible factors of successful crowdfunding campaigns based on the dataset, including 4,000 crowdfunding projects information. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 
The attached line chart resources/Outcomes_vs_Goals.png shows the different outcomes of Theater crowdfunding based on the launch date. It is clear that successful and failed outcomes have the same upward trend before May and downward after that month. Starting from 56 results successful make the crowdfunding for the theater. This figure experiences fluctuation before dramatically increasing to the peak of about 111 success in May, before dropping consistently to reach the third-lowest level of 59 in September. In contrast, the number of cases that failed to raise enough money for the campaigns was only half, and even less of those met the target cases in the most period. After this, this number fluctuated and slightly reached the highest point of 52 in May, followed by a marginally drop until September and a rapid rise in October. However, the data displayed a dramatic decrease trend in November and a minimal increase at the end of December. Thereafter, both followed a very similar result in December and the same peak time in May. On the other hand, the number of cancelled campaigns remained stable, and fewer happened than the other two situations, no more than ten monthly around the year. Nonetheless, in October, there was no cancelled crowdfunding campaign created. 

### Analysis of Outcomes Based on Goals
The graph displays the number of changes in three crowdfunding outcomes (successful, failed and cancelled) in different goal amount ranges. Starting at 71%, the successful percentage reach the highest point in the field, less than $1,000. After that, there was a gradual downward trend in success rate with the increasing goal range below $35,000. Then followed by a slight rise between goal amount of $35,000 to $45,000, before sharply drop to the lowest point of 19% on the goal greater than $50,000. However, beginning from the lowest 25% in failed percentage trend, which has the most contrast display compared to the successful one. In addition, the cancelled percentage experienced a fluctuation and consistent an upward trend, reaching the peak on the goal amount over $50,000 at the end. 

### Challenges and Difficulties Encountered
When I figured out the column of Percentage Funded on the Kickstarter workbook, it failed to display colour gradient. I tried a lot of time in conditional formatting and colour scale, but it did not work. So I search through the Google Internet to find answers. Finally, I noticed that this is a percentage column, requiring me to change the type to percent in the formatting rule and enter the extremum values to show the gradient. 


## Results

### Two Conclusions of the Outcomes Based on Launch Date
1. we can conclude that the second quarter, especially May, has the highest number of successful crowdfunding campaigns. It shows that raising funds for the project is the easiest to succeed at this time. Also, it is the most challenging time to raise money in the fourth quarter because of the lowest successful and highest failed outcomes. 
2. the number of cancellations of activities had always maintained a stable trend throughout the year, indicating a probability of occurrence every month. Therefore, it is less relevant to the prediction of the success of fund-raising. And there may be other factors that caused the cancellation of the event, such as extreme weather.

### Conclusion of the Outcomes based on Goals
There is an opposite direction between success and higher goal amount range. The higher the goal range, the lower the successful percentage, the higher failed percentage. 

### Limitations of the dataset 
Based on Category Statistics fliter by country, I found that this dataset mainly focus on US and GB, which is not comprehensive enough to analyze all the areas.

### Other possible tables and graphs 
We could create the graph of Outcome based on pledged to analyze the amount people actually willling to pay on these projects. Also, we can figure out which year has the highest average donation between 2009-2017.
