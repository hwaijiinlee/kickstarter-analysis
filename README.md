# Kickstarting with Excel
## Overview of Project
Louise saw success in her fundraising efforts for the play *Fever* and is keen to understand how other campaigns fared.
### Purpose
This analysis is performed to investigate the outcomes of theater-related campaigns based on their launch dates as well as how campaigns for plays fared based on their fundraising goals.
## Analysis and Challenges
Data of all campaigns launched from 2009 to 2017 on the Kickstarter platform is obtained for this analysis. In order to differentiate campaigns for plays from the other theater-related campaigns the category and subcategory had to be separated into Parent category and subcategory.
### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Date]( https://github.com/hwaijiinlee/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

From 2009 to 2017, there were a total of 1,369 completed campaigns, out of which 839 or about 61% were successful. The largest proportion of those successful campaigns launched in May followed closely by June. Campaigns launched in December form the smallest proportion of the 839 successful campaigns. 

Failed campaigns form about 36% of the total completed campaigns. Campaigns with October launch dates form the largest proportion of those failed campaigns, and campaigns with December launch dates appear to have almost equal chances of being successful as failing.
### Analysis of Outcomes Based on Goals
![Outcomes Based on Goals]( https://github.com/hwaijiinlee/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

There were 1,047 completed plays-related campaigns from 2009 to 2017. 694 or about 66% were successful. Campaigns with goals less than 1,000 have the highest rate of success. Campaigns with goals greater than 50,000 has the lowest chance of achieving their goals, taking into consideration there was only one campaign with a goal between 45,000 and 49,999 and it failed.
### Challenges and Difficulties Encountered
While determining the number of successful, failed and canceled campaigns for plays, it was important to not double count campaigns with the CountIfs formula since the formula by itself can only accommodate values that are either less than, greater than, or equal to a single number rather than being capable of extracting outcomes based on two numbers.
## Results
Based on the above analyses, we can conclude that 
1)	most theater-related campaigns have favorable outcomes; 
2)	launching those campaigns in May or June tend to have a much higher success rate than launching them in December; and
3)	plays-related campaigns would do well to keep their fundraising goals less than 4,999.

It is important to note that the above analyses do not take into consideration the country in which the campaigns are launched, the Purchasing Power Parity of the goals, nor the currency in which the goals were published. We can perhaps draw a better conclusion if we were to narrow down the analysis to the country in which prospective fundraisers are going to raise funds from or have graphical representation of the outcomes by country as well.
