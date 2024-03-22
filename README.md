# A Comparative Study of Homeless Populations in Texas and California

Team: Isha Chaware, Alexandra Turner, Nancy Ulloa, Arlie Alcid, Beauty Simora

Motivation: 
Homelessness is a complex and pressing issue that affects millions of individuals and families in the United States. To better understand the evolving nature of homelessness and formulate effective policies and strategies, a comprehensive decadal survey is proposed to examine the impact of various factors on homelessness in the USA from 2013 to 2020. This survey will provide crucial insights into the causes and dynamics of homelessness, enabling policymakers, researchers, and service providers to develop evidence-based interventions and policies.

Questions: 
1. Are some race groups affected by homelessness more than others?
2. What is the correlation between gender and homelessness?
3. Does the homeless distribution vary according to age groups?
4. What is the count of veterans experiencing homelessness?
5. What is the overall total homeless population taking advantage of CoC shelters available in the area?

Table of Contents:
Age - Code and graphs comparing the sum of different age groups in the homeless population between Texas and California. As well as an analysis on the age group in an 8 year span.

Gender - Code and graphs depicting the distribution between genders in the homeless population for Texas and California, and analysis summarizing the changes through a 6 year span. 

Overall Average - Code and graphs comparing the overall total homeless population for Texas and California through an 8 year span, as well as an analysis for the correspoding graphs.

Race - Code and graphs that depict the 3 most affected races (Non-Hispanic/Non-Latino, White, and African American/Black) through a 6 year span, as well as the sheltered and unsheltered sum. An analysis to describe the different race demograpics for Texas and California.

Veterans - Code and graphs comparing the average total for homeless veterans in Texas and California, through an 8 year span, as well as comparing the sheltered and unsheltered veterans in both states. An analysis to summarize the homeless veteran population change throughout 8 years. 

Datasets to be Used:
Office of Policy Development and Research (PD&R) - Estimates of Homelessness in the United States 2007 - 2020 Point-in-Time Estimates 
by CoC - https://www.huduser.gov/portal/sites/default/files/xls/2007-2020-PIT-Estimates-by-CoC.xlsx 2007 - 2020 Point-in-Time Estimates 
by State - https://www.huduser.gov/portal/sites/default/files/xls/2007-2020-PIT-Estimates-by-state.xlsx 2007 - 2020 PIT Veterans Counts 
by CoC - https://www.huduser.gov/portal/sites/default/files/xls/2011-2020-PIT-Veteran-Counts-by-CoC.xlsx

Cleaning Data:
After a path was created to each Excel file on Jupyter, Pandas and MatplotLib were imported in order to read the data and create graphs. Texas and California were filtered for the datasets, and graphs were made accordingly to the available data. 

Overall Analysis:
Age - Homeless population in Texas for age group - Under 18 - is decreasing in mid years and then there's a rise as move towards 2020. 18 to 24 - is approximately same for all 7 years. Above 24 - is Significantly increasing as we move towards 2020. Graphs demonstrate that for population in the group above 24, Texas witnesses a significant fall in 2020 as compared to 2013 and a gradual rise in California in the same span of years. Population of age above 24 is majorly affected by homelessness in both the states.

Gender - Overall male homeless population is greater than the female and transgender. California has the greater population of transgender homeless individuals. Females are the least sheltered gender for both states. Male  sheltered population shows a gradual increase over the years. 

Overall Average - The analysis shows that California has experienced a significant increase in homelessness, particularly in unsheltered populations, while Texas has seen a slight decrease in total homelessness. The combined analysis highlights the contrasting situations in the two states, with California facing a more severe homelessness crisis. 

Race - Similar to the California dataset there appears to be an increase in the overall amount of homeless non-hispanic/non-latino indiviuals as the years go by. Unlike the California dataset, the amount of sheltered non-hispanic/non-latino indiviuals appears decrease as time goes by. The amount of unsheltered non-hispanic/non-latino indiviuals appears to fluctuate between the years of 2015 and 2019, however, there is a sharp increase from 2019 to 2020 which may be explained by various cofoundings including the start of hte covid 19 pandemic. Although it is not stated in out dataset, this decreasing trend of sheltered individuals may be due to a decrease in homeless shelter funding or resources or homeless individuals simily choosing not to seek shelters. It is important to note the y-axis range of the California and Texas overall homeless non-hispanic/non-latino graphs. California contains over 100,000 individuals, whereas Texas contains less than 20,000 individuals. This may indicate that California overall has greater homeless population.

Veterans - By comparing the bar graphs for Texas and California, it is clear that Texas had the greater overall drop in homeless Veterans. Texas has an overall 49.86% decrease in homeless veterans, whereas California only had a 12.42% decrease. Texas shows that a significant greater amount of homeless veterans made use of homeless shelters over the years, while California had nearly over 50% of homeless veterans not making use of homeless shelters in their area. This could be due to many factors, such as government funding, or general lack of other resources (such as mental health care/addiction) for the veterans.

References:
https://www.huduser.gov/portal/datasets/ahar/2020-ahar-part-1-pit-estimates-of-homelessness-in-the-us.html
https://www.huduser.gov/portal/sites/default/files/xls/2007-2020-PIT-Estimates-by-CoC.xlsx
https://www.huduser.gov/portal/sites/default/files/xls/2007-2020-PIT-Estimates-by-state.xlsx
https://www.huduser.gov/portal/sites/default/files/xls/2011-2020-PIT-Veteran-Counts-by-CoC.xlsx
https://soarworks.samhsa.gov/article/definitions-of-homelessness#:~:text=The%20definition%20of%20those%20who,not%20meant%20for%20habitation%2C%20or
https://www.texastribune.org/2023/01/26/texas-homeless-veterans-affairs-va/#:~:text=Texas%20and%20California%20have%20the,the%20beginning%2C%E2%80%9D%20McDonough%20said
lendingtree.com/home/mortgage/homelessness-study/

We would also like to give credit to our TA's and tutors for guidance and patience throughout the project, as well as to ChatGPT for the moments we felt stuck in our code. 

