# Are some race groups affected by homelessness more than others?


### Cleaning the data - 
In order to begin my EDA, I loaded in the Point-in-Time Estimates by State dataset from the Office of Policy Developement and Research and named the excel file demostate.xlsx. I was only interested in looking at the homeless individals in California and Texas, so I filterd the rows by cells containing Ca and Tx. 

The biggest issue with our data cleaning was that the demostate excel workbook contained multiple individual datasheets which were labeled by the corresponding year, and all column names within each datasheet also had the year. For example, there was a 2020 dataset for all data collected in 2020 and each column named ended with "2020", thus it was difficult to combine like data by column names. I solved this issue by creating a new column containing the corresponding year and removed the year from the column names. For example:  “Overall homeless - Asian, 2020” was renamed to “Overall homeless - Asian”. Some of the datasets contained over 540 columns, so to narrow down the data I chose to only keep columns containing the overall, sheltered, and sheltered variables related to the eight main racial groups: Non-Hispanic/Non-Latino, Hispanic/Latino, White, Black or Afircan American, Asian, American Indian or Alaska Nativem Native Hawaiian or Other Pacific Islander or Multiple Races. Finally I created combined dataset by merging the desired rows, states, with the desired columns.


### Visual Analysis: Overall Homeless Individuals in California and Texas - 
To begin my visual data analysis I created a bargraph with the combined California and Texas dataset. The x-axis represents the years 2015 - 2010 in which racial data was collected, and the y-axis represents the total amount of overall homeless individuals in the states of California and Texas.

Based on the bar graph Non-Hispanic/Non-Latino (blue), White (green), and Black or African American (red) appear to be the three most affected races by overall homelessness. Whereas other groups such as Asian, Native Hawaiian or other Pacidic Islander, and multiple races appear to be less affected. One reason this that could explain this trend is that there are likely a lot more indiviuals in these states that identify as Non-Hispaic, White, or Black than individals that identify as Asian, Native Hawaiian, or as multiple races. Another thing to point out in this graph is there appears to be an increasing trend of overall homelessness in the three main race groups overtime. 


### Visual Analysis: Non-Hispanic/Non-Latino Individuals in California 
The cleaned dataset for the combined California and Texas data contained many levels too many variables to include on one single graph. In order to make the data easier to look at, I created two new dataset called combined_ca to include only data from Califonia and combiend_tx to includeonly daya from Texas. 

To visualize the trends within each racial indentification group, I created a clustered bar graph to compare the overall total count of homeless individuals within a single racial group with the sheltered and unsheltered total counts. In this case, I chose to look at only individuals identifying as non-hispanic/non-latino because they appeared to be the group with the most amount of overall homeless individals as seen in the previous graph. 

   Trends:
There appears to be an increase in the overall amount of homeless non-hispanic/non-latino indiviuals as the years go by. The amount of sheltered non-hispanic/non-latino indiviuals appears to stay relatively stable which may indicated that there is a capacity of the amount of individuals that can reside within shelters. For example, if there are only 100 beds in a given shelter, at any given time there can only be 100 indiviudals in the shelter. THe amount of unsheltered non-hispanic/non-latino indiviuals appears to fluctuate between the years of 2015 and 2019, however, there is a sharp increase from 2019 to 2020 which may be explained by various cofoundings including the start of the Covid 19 pandemic. 


### Visual Analysis: Non-Hispanic/Non-Latino Individuals in Texas 
I created a subsequent cluster bar graph to visualize the overall, sheltered, and unsheltered homeless non-hispanic/non-latino indiviual in the state of Texas. 

  Trends:
Similar to the California dataset there appears to be an increase in the overall amount of homeless non-hispanic/non-latino indiviuals as the years go by. Unlike the California dataset, the amount of sheltered non-hispanic/non-latino indiviuals appears decrease as time goes by. The amount of unsheltered non-hispanic/non-latino indiviuals appears to fluctuate between the years of 2015 and 2019, however, there is a sharp increase from 2019 to 2020 which may be explained by various cofoundings including the start of hte covid 19 pandemic. Although it is not stated in out dataset, this decreasing trend of sheltered individuals may be due to a decrease in homeless shelter funding or resources or homeless individuals simily choosing not to seek shelters. It is important to note the y-axis range of the California and Texas overall homeless non-hispanic/non-latino graphs. California contains over 100,000 individuals, whereas Texas contains less than 20,000 individuals. This may indicate that California overall has greater homeless population. 


### Statistical Analysis: Anova comparing the overall, sheltered, unsheltered non-hispanic/non-latino homeless individuals in Texas - 
  Ho = There are no significant differences among the homeless groups non-hispanic/non-latino individuals in the state of Texas. 
  Ha = There is a significant difference among at least one of the homeless groups non-hispanic/non-latino individuals in the state of Texas.

Since the p-value < 0.05 there is evidence to reject the null hypothesis in favor of the alternative hypothesis. At least one of the homeless groups of non-hispanic/non-latino individuals in the state of Texas is significantly different than the others. A Tukey's test or Bonferroni correction can also be performed to identify which specific groups differ from each other.


### Statistical Analysis: Anova comparing the overall, sheltered, unsheltered non-hispanic/non-latino homeless individuals in California - 

  Ho = There are no significant differences among the homeless groups non-hispanic/non-latino individuals in the state of California. 
  Ha = There is a significant difference among at least one of the homeless groups non-hispanic/non-latino individuals in the state of California.

Since the p-value < 0.05 there is evidence to reject the null hypothesis in favor of the alternative hypothesis. At least one of the homeless groups of non-hispanic/non-latino individuals in the state of California is significantly different than the others. A Tukey's test or Bonferroni correction can also be performed to identify which specific groups differ from each other.
