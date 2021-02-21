# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this data analysis is to compare outcome performance of theater campaigns based on launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Starting the analysis, a new column capturing the year the campaigns launched using the formula YEAR()in the Kickstarter data was added. The Kickstarter data was cleaned ensuring all filters and rules were disabled. A pivot table and a line graph were created in a separate sheet. The campaign category and year were filtered in the new sheet. The outcomes were chosen as columns, the count of outcomes as values, and the date launched as rows. Launch dates were grouped as months in the pivot table. Lastly, the outcomes were sorted by descending. 

The line graph generated at the same time as the pivot table. The graph was titled and a legend was added using the chart element options.  The fields within the chart were deleted. Lastly, a graph design was chosen (See Theater Outcomes Based on Launch Date). 

### Analysis of Outcomes Based on Goals

To continue the analysis, a separate sheet was created focusing on campaign outcomes based on goals. A dollar amount range capturing the goal amount was created. The formula COUNTIFS extracted the campaign outcomes excluding lived campaigns from the Kickstarter data. The sum outcome per range was calculated for successful, failed, and canceled campaigns. Lastly, dividing the number of outcomes to the total number of projects generated the range percentage.

A pivot table and a line graph were created on a separate sheet reflecting the outcomes of the campaigns based on goal. The goal range was chosen as rows and re-arranged from smallest to largest while the sum of outcome as values but changed to percentages in the pivot table.

Concluding the analysis, a title and legend were included in the line graph. The legend was moved to the bottom of the graph. Lastly, a graph design was selected (See Theater Outcomes Based on Launch Date).

### Challenges and Difficulties Encountered

A few challenges and difficulties occurred during the analysis. The filters and rules in the Kickstarter data generated blank cells after calculating the year. This issue first appeared in the pivot table and was fixed in the Kickstarter data by following instructions researched using Google. Although the issue was fixed, ways to update the data in the pivot table caused difficulties and the only solution was to re-start a new sheet. Although it seemed like a challenge at the time, the repetition helped with memorization of the process.
 

Using the formula COUNTSIFS was also difficult. At times, there were missing commas or quotations. A fellow classmate helped identify the issues. Cutting and pasting the first formula into the remaining cells helped with the rest of the formulas; however, there is an easier method: use $ to lock the formula.  

The last difficulty was matching the line graph to the example provided in the deliverable. The identification of the unidentical points in the graph revealed the need to re-arrange the rows in the pivot table. Once this step was done, the line graphs matched. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first conclusion drawn from the Outcomes based on Launch Date is that there is about a 50/50 chance of succeeding or failing when launching a theater campaign in December with a low chance of being canceled. The second conclusion is that May and June are popular months for launching a theater campaign. The line graph shows these months as having the highest numbers of successful campaigns but about half of the total failed.  

- What can you conclude about the Outcomes based on Goals?

The conclusion for Outcomes based on Goals is that there is no correlation between the goal and the outcome. 

- What are some limitations of this dataset?

This dataset has limitations. The low sample size hindered generalization about the success of launching theater campaigns. Also, adding data will further this analysis. For instance, were the campaigns launched in rural or urban locations? Further exploration on number of backers versus outcomes would also assist this analysis.        

- What are some other possible tables and/or graphs that we could create?

Other possible tables and/or graphs can be created for this analysis. The percentages for successful, failed, and canceled theater campaigns can be calculated to show the outcomes based on launch date as well as a pivot table and line graph showing the percentages. Individual bar graphs for each outcome can be generated. The outcomes based on goals can be displayed with a stacked bar graph. 