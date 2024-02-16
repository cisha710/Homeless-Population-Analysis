
# Project-1
##Project 1 - A Comparative Study of Homeless Populations in Texas and California

Team Members: Alexandra Turner, Arle Alcid, Beauty Simora, Isha Chaware, & Nancy Ulloa

# Project Description/Outline
Homelessness is a complex and pressing issue that affects millions of individuals and families in the United States. To better understand the evolving nature of homelessness and formulate effective policies and strategies, a comprehensive decadal survey is proposed to examine the impact of various factors on homelessness in the USA from 2013 to 2020. This survey will provide crucial insights into the causes and dynamics of homelessness, enabling policymakers, researchers, and service providers to develop evidence-based interventions and policies.

#Research Questions to Answer
1. Are some race groups affected by homelessness more than others?
2. What is the correlation between gender and homelessness?
3. Does the homeless distribution vary according to age groups?
4. What is the count of veterans experiencing homelessness?
5. Overall total homeless population taking advantage of CoC shelters available in the area?


# Datasets to be Used
Office of Policy Development and Research (PD&R) - Estimates of Homelessness in the United States
2007 - 2020 Point-in-Time Estimates by CoC - https://www.huduser.gov/portal/sites/default/files/xls/2007-2020-PIT-Estimates-by-CoC.xlsx
2007 - 2020 Point-in-Time Estimates by State - https://www.huduser.gov/portal/sites/default/files/xls/2007-2020-PIT-Estimates-by-state.xlsx
2007 - 2020 PIT Veterans Counts by CoC - https://www.huduser.gov/portal/sites/default/files/xls/2011-2020-PIT-Veteran-Counts-by-CoC.xlsx


# Cleaning Data
- Uploaded 2007 - 2020 Point-in-Time Estimates by State - https://www.huduser.gov/portal/sites/default/files/xls/2007-2020-PIT-Estimates-by-state.xlsx file in Jupyter.
- Data was filtered and added a new column - 'Year'.
- Required rows and columns for the states Texas and California were pulled from each sheet from 2013-2020.
- A new dataframe - combined_data was created for TX and CA data
- Two new dataframes - combined_data_TX and combined_data_CA were created from the above dataframe.

# Summary
![HomelessVSAgeTexas](https://github.com/ajturner3/Project-1/assets/143370584/f6077641-0b22-4133-9f0a-66440a455713)

- Homeless population in Texas for age group - Under 18 - is gradually decreasing as the years pass by. 18 to 24 - is approximately same for all 7 years, but can see a small decrease in 2019 and 2020. Above 24 - is Significantly decreasing for mid years but can see an increasse again from 2018-2020.

![HomelessVSAgeCA](https://github.com/ajturner3/Project-1/assets/143370584/b4c05bf3-c9f4-4439-8f32-a9641b5b5437)


- Homeless population in Texas for age group - Under 18 - is decreasing in mid years and then there's a rise as move towards 2020. 18 to 24 - is approximately same for all 7 years. Above 24 - is Significantly increasing as we move towards 2020.
- Above graphs clearly state that for population in the group above 24, Texas witnesses a significant fall in 2020 as compared to 2013 and a gradual rise in California in the same span of years.
- Population of age above 24 is majorly affected by homelessness in both the states.
