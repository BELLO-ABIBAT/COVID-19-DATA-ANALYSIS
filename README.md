# COVID-19-DATA-ANALYSIS

A project analyzing the global impact of COVID-19

##  INTRODUCTION
Covid’19 caused by the SAR-CoV-2 virus is a global pandemic that as ravaged the world since its emergence in late 2019. The disease infected millions, claiming countless lives and disrupting economies, societies and healthcare system in the world. Covid’19 pandemic has generated an unprecedented amount of data offering insights into the virus spread, severity and societal impacts. analyzing and interpreting this data can reveal trends, patterns and policy response and optimizing resource allocation.

###  RESEARCH QUESTIONS
1.	How has number of covid’19 cases changed over the years?
2.	Which locations have the highest number of covid’19 new cases?
3.	Which year and month do covid’19 cases occur the most in United State?
4.	Which location have the highest number of covid’19 death?
5.	Which location has the highest number of survived cases?
6.	What is the impact of the new vaccination on covid’19 cases and new death?
7.	What is the relationship between covid’19 new tests and the positivity rate over the years?
8.	How has COVID-19 new cases impacted key economic indicators GDP capita growth in each location?
9.	How does access to hand wash facilities impact covid’19 death in each continent?
###  DATA ANALYSIS PROCESS

####  Data Collection
Data was collected from the covid’19 site https://ourworldindata.org/covid-deaths in an excel format.
####  Data Transformation
After downloading the data set, the dataset was import into power bi using get data.


After which the dataset went in to the transform stage of the power query editor, I removed columns that are not needed, rename the dataset to COVID’19, changing the datatype, renaming each column to make sure the column header indicates the content of that column and also replacing the null values in each column with 0, Filtered some rows
 

 
Duplicate the dataset three times, Renamed the 3 duplicated dataset as follows location, date, facts I duplicate the dataset in order to build model and create relationships between them, After creating tables I removed duplicates from each table and disable the covid’19 dataset from loading.
 
The clean data was loaded from the power query editor into the field pane of power bi itself after which a calculation was carried out using DAX expression in order to create measures.
 
After which a model was created between the tables to show the relationship between the tables
 

A dashboard was then created for visualization of the dataset
 



###  Descriptive statistics
  -  Sum of new cases = 775.73M
  -  Average number of new cases = 1.97k
  -  Sum of new vaccination = 10.86BN
  -  Sum of new death = 7.06m
  -  Average sum of new death = 17.94
  -  Sum of survived cases = sum of new cases – sum of new death = 768.67m
  -  Sum of new test = 5.07bn
  -  Average sum of new test = 12.90k
  -  Sum of positive rate = 9.41k




###  KEY FINDINGS
####  How has number of covid’19 cases changed over the years
The analysis shows that the number of Covid’19 cases increase in 2020 due to the outbreak of covid’19 by 2022 the number of cases has reached it peaked which might be due to the spread of more transmissible variant by 2023 and 2024 the number of cases has decreases from 424,014,285 in 2022 to 69,273,009 and 1,834,848 in 2023 and 2024 respectively this might be due to the impact of vaccination and public awareness.
#### Which location that has the highest number covid’19 cases?
The analysis shows that United state has high number of Covid’19 cases with 103,436,829 number of cases these might be due to large populations, resistance to mask-wearing and social distancing.
#### Which year and month covid’19 new cases occur the most in United state?
The analysis shows that January 2022 has the highest number of covid’19 cases compared to December 2022 with a total number of 94,692,404 indicating a peak in the pandemic during this period this might be due to the ease of lock down and social gatherings during the holiday season.
####  Which location have the highest number of covid’19 death?
The analysis shows that the location with the highest number of death rate is United States with 1,190,579 death these might be due to healthcare capacity and public health responses.
####  Which location has the highest number of survived cases?
The analysis shows that United States has the highest number of survived cases with about 102,246,250 million this might be due to the advancements in medical treatments, widespread vaccination efforts and improved healthcare access over time.
####  What is the impact of the new vaccination on covid’19 death on each continent?
The analysis shows that that after the roll out of the new vaccination in each continent there is a decrease in the number of covid’19 cases and new death. continent such as Asia, Europe, Africa, north America, south America and Oceania has reduced number of new cases and new death this might be due to the effectiveness of the new vaccination and the vaccination campaign in each continent.
####  What is the relationship between covid’19 new tests and the positivity rate over the years?
The analysis shows that as individuals are tested the positivity rate decreases from 2020 to 2024 these might be due to more broader screening which shows the improved testing capacity and decrease in transmission rate.
####  How has COVID-19 new cases impacted key economic indicators like GDP capita growth in each location?
The analysis shows that locations with higher covid’19 new cases experience decrease in GDP capital location such as USA, Brazil, China and India these might be due to the struggle to enforce strict lockdowns due to economic constraints and reliance on daily labor. Locations with high GDP such as France and Germany maintained a strict lockdown measures.

####  How does access to hand wash facilities impact covid’19 death in each continent?
The analysis shows a negative impact between handwash facilities and covid’19 new death in most continent. Continent such as Europe, north America, south America has low access to handwash facilities show higher covid’19 new death which might be due to lack or limited access to handwash facilities in those continents while Asia, Africa and Oceania have higher access to handwash which lower covid’19 new death.






















###  RECOMMENDATION
Continuous vaccination effort and public health measures to reduce transmission.
Targeted public health interventions in regions with high number of covid’19 cases.
Enhanced surveillance and monitoring in areas with high number of cases.
Investing in infrastructural to increase access to handwashing facilities.
Promote hand hygiene practices through public awareness and campaigns.
International support and fundings.
####  CONCLUSION
The analysis of COVID-19 case data reveals key trends that can inform public health policies and intervention strategies. Peaks in case numbers are often associated with colder months, increased social gatherings and limited public health restrictions. Vaccination campaigns when targeted and timed effectively have a significant impact on reducing the spread of the virus. 
Furthermore, transparent communication of case trends and proactive policies around testing, tracing and vaccination are essential to controlling the spread of COVID-19. integrating real-time data with public health decision-making will be crucial for managing future outbreaks especially as new variants emerge. The data highlights the importance of ongoing vigilance, flexibility in policy and the need for collaborative efforts to ensure effective responses to pandemics.

