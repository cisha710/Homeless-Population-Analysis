Average homeless veteran analysis for an 8 year span

Uploading and cleaning the data:
1. The dataset "2011-2020 PIT Veteran Counts by CoC" from "huduser.gov" was used in order to find total populations for the state of California and Texas. I saved the excel file       as "veteran_data_set.xlsx" and created a path to it on Jupyter.
2. Texas and California were filtered out from the excel file sheets
3. The average count of total homeless veterans, sheltered veterans, and unsheltered veterans was calculated using ".mean()" and rounded to the nearest whole number.
4. A new DataFrame was created, in order to put all the averages for both states together, with an index set to "Years"
5. A total percent difference from year 2013 to year 2020 was calculated using iloc[0] and iloc[-1], and then dividing the two rows and multipyling by 100
6. Pandas and MatPlotlib were used in order to create a bar graph depicting the average change through an 8 year span for Texas and California.

Analysis:
By comparing the bar graphs for Texas and California, it is clear that Texas had the greater overall drop in homeless Veterans. Texas has an overall 49.86% decrease in homeless veterans, whereas California only had a 12.42% decrease. Texas shows that a significant greater amount of homeless veterans made use of homeless shelters over the years, while California had nearly over 50% of homeless veterans not making use of homeless shelters in their area. This could be due to many factors, such as government funding, or general lack of other resources (such as mental health care/addiction) for the veterans. 
