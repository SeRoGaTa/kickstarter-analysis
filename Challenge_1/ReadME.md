# Kickstarting analysis with Excel tools

***Version 1.0.0***

---

## Overview of Project
#### This project analyzes the data gathered of a some campaigns in several countries comparing them with theirs goals, pledges, outcomes and launching dates among other characteristics so we can have helpful insights and take better and quick decisions.

## Purpose
#### This analysis will help Louise understand how different campaigns fared in relation to their launch dates and their funding goals now that her is coming close to its fundraising goal. This analysis will be focused in the campaigns by launch date, goal and outcomes. 

---

## Analysis and Challenges
#### On this analysis I took two approaches, the first one analyzes the campaigns based on their launch dates and see which ones were more successful depending on their launch    month and the second analysis is focused on how success a campaign were depending on their goal range. The challenge here was to define the goal ranges for the analysis and     validate if the granularity tells us a good story and then to split all the campaigns by dates due to it’s particular way to express this fields on the data set (Unix type).

### - Analysis of Outcomes Based on Launch Date
#### As we can see in the following chart, it's quite clear that the best month to launch a successful campaign is in May, but that peak is also maintained during the following 2 months, so we can conclude here that summer is a good time to launch a campaign. 

<img src="https://github.com/SeRoGaTa/kickstarter-analysis/blob/main/Challenge_1/Resources/Theater_Outcomes_vs_Launch.png" width="800">

### - Analysis of Outcomes Based on Goals 
#### On this chart is telling us the best goal range in where successful campaigns are located. As we see, the most successful campaigns are in the low (left part of the chart) goal ranges. We can deduce out of this chart than the lower the goal is, there’s a better chance to have a successful campaign.

<img src="https://github.com/SeRoGaTa/kickstarter-analysis/blob/main/Challenge_1/Resources/Outcomes_vs_Goals.png" width="800">

### - Challenges and Difficulties Encountered
#### One of the challenges of the data is how the dates are deployed, as we can see in the original data, dates are in a format we need to transform it to use it in all the further calculations. Other difficulty regarding the goals I encountered was to choose the right granularity of the goal ranges so the chart could reflect a visual difference between the outcomes, here I propose to have a pie chart with the top 3 months where successful outcome is high vs failed. This could be a faster way to locate the good season to launch a campaign.

---

## Results

* What are two conclusions you can draw about the Outcomes based on Launch Date?
   - The first conclusion I got out of the chart of Outcomes and Launch dates is that the Successful and Failed campaigns are following quite the same trend, I see the same ups and downs in both lines besides 3 specific months, so at the end we might expect quite similar behavior most of the year for both outcomes.
   - My second observation of the data is that summer is a differentiator of these trends between successful and failed campaigns, we might assume that summer break on the schools could affect the behavior of the campaigns.

* What can you conclude about the Outcomes based on Goals?
   - We can say out of our analysis of goals and outcomes that the successful outcome decreases if we increase the goal sum, most of the successful outcomes are located in the left side of the chart which tell us that less goal sum has more chances to have a successful campaign. 

* What are some limitations of this dataset?
   - One limitation I see with this data set is the campaigns by country, I see the data mainly focused on US and GB countries (holding more than 90%). This will skew the analysis to what these two countries says so this column data at the end won’t help us to analyze the data, other limitation we have is we have a lot of parent categories and subcategories that will split the info into many pieces, we might need some clusters here to really get more general insights of the data to get a 5000 ft view. 
   
* What are some other possible tables and/or graphs that we could create?
   - The year will help us to understand how this campaigns behavior have changes across the time, we could create some charts of how the outcomes have changed between the times and add the average of goals to the chart, we might get a relationship between goals, outcome and time that helps understand the history and with this create some forecast to the future campaigns. Also, we could add more dimensions to the data like reasons of failed or canceled campaigns, with this we can locate the factors that affect the campaigns and minimize them so more campaigns could be successful. Here we could add some analysis like pareto or scatter charts so we could focus on the main problems and solve them.

You can locate the complete analysis file on the following link [Kickstarter Analysis](https://github.com/SeRoGaTa/kickstarter-analysis/blob/main/Challenge_1/Kickstarter_Challenge.zip)
