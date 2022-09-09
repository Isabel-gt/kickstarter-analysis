# Kickstarting with Excel 

## Overview of Project
Louise launched a crowdfunding campaign for a play called *Fever*. Her campaign almost achieved the fundraising goal. However, she wants to have more information about the outcome of other campaigns such as the outcomes of those projects in relation to their launch dates and their funding goals. 

### Purpose
The objective of this analysis is to give Louise more information about theater campaigns outcomes based on the two aspects mentioned above. Having a big data set with information about different types of projects will help us sort the information to help Louise. 

## Analysis and Challenges
There were two analyses performed in order to achieve the purpose of this project. First, an analysis of outcomes based on launch date. The second was an analysis of outcomes based on funding goals. Nevertheless, there were certain difficulties encountered while executing the analyses. 

### Analysis of Outcomes based on Launch Date
First of all, in the main sheet named *Kickstarter* a column named *Years* was added to make it easier to spot the year each campaign was launched. 

<img width="500" alt="year_colums" src="https://user-images.githubusercontent.com/111388644/189015784-e43cf1af-451c-493a-9a7a-555287feb407.png">

Then, with all the data from the main sheet a pivot table was made. In the table the rows show the months of the launching date of each campaign and the columns exhibit whether those projects were successful, failed, or canceled. To make the analysis more precise the data was filtered to display only the information of the category *Theater*.

<img width="200" alt="pivot_table_launchdates" src="https://user-images.githubusercontent.com/111388644/189211319-1fbfa8a3-d2f2-4e47-9c6a-4fe98c7702ce.png">

Finally, a pivot chart was created. In the chart the information of the table is shown. This visualization item is useful to see the data in a more organized and understandable way. It also makes drawing conclusions about the information easier. 

<img width="353" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/111388644/189015345-5f19e757-7794-445b-8401-ccb29800ef01.png">

### Analysis of Outcomes Based on Goals
In order to make this analysis it was necessary to create a new sheet showing new information regarding the data in the *Kickstarter* sheet. In the main sheet the data was filtered so that the calculations in the new sheet included only the information of the subcategory *plays*. In the new space of work the rows display different ranges of money depending on the funding goal each campaign had. In the columns the number of successful, failed, and canceled projects was calculated using the Excel formula **COUNTIF**, as well as the total number of projects using the formula **SUM**. After that, the percentage of each outcome was calculated. 

<img width="500" alt="Percentages_outcomes_and_goalss" src="https://user-images.githubusercontent.com/111388644/189210607-4081208d-a30a-406a-911d-3996cf6132d2.png">

At last, a line graph was made containing the percentages of the outcomes in addition to the funding goals range. Having the graph allows the data to be displayed in an attractive form and makes its interpretation faster. 

<img width="346" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/111388644/189211465-5aa6345e-c0ff-49bf-a41c-4193e3cfb0a8.png">

### Challenges and Difficulties Encountered
While doing this analysis I struggled doing the visualization part. Being able to make the graph in an organized way was challenging. In the first attempts I was able to display the graph, but the data in the row section was not in order, so I had to create a pivot table first and afterwards the chart. Viewing the table was key to organize the data in the rows. After searching in google how to move elements inside a pivot table I was capable of arranging the information, consequently changing the chart into the desired form. 

## Results
-What are two conclusions you can draw about the Outcomes based on Launch Date?
 1. The peak month of the successful theater campaigns was May with more than a hundred plays, followed by June with a hundred plays exactly. Although May was also the peak month of the failed outcomes having fifty campaigns failed, still may or June seem to be good months to launch a campaign. This is because the number of successful projects is two times bigger than the number of failed ones.
 2. The month of December would be one of the least recommended dates to launch a project, since it was the less successful month with a number of thirty-seven campaigns. During this same month thirty-five-projects failed. 
 
-What can you conclude about the Outcomes based on Goals?

The best amount of money for Louise to set as a funding goal for future projects would be less than a thousand to forty-nine thousand nine hundred ninety-nine dollars. We can conclude this because the campaigns with that goal range were more than seventy percent successful. In the other hand, the worst funding goal range would be forty-five thousand to forty-nine thousand nine hundred ninety-nine dollars because when setting those amounts as a goal a hundred percent of the projects failed. 

-What are some limitations of this data set?

There are certain limitations within this data set, for example: it could include more information like the states or the cities where each campaign was launched at. This would give a more precise perspective of the data and it would also allow to reach more exact conclusions. Another example of the same limitation would be to add the genre of the theater plays. If other elements of the data ser were to be analyzed, then there would be more in depth in the conclusions to make better decisions.
Although it is possible to draw conclusions viewing how well the campaigns did based on the funding goal or on the launch date, with this data set it is hard to explain the exact reasons for the outcomes of the campaigns. This is because other variables such as: the interest of the backers in the project, whether the campaign is feasible or not, among others, may have affected the outcomes.

-What are some other graphs and/or tables we could create?

There are other graphs that could be created, for example: a graph that shows the outcomes depending on the (place) country in which the campaign was launched. Another example could be a table where the outcomes were based on the number of backers the projects had. And also, a graph comparing each theater subcategory with their outcomes. 
