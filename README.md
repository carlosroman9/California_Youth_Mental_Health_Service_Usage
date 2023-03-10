# California_Youth_Mental_Health_Service_Usage

Project: Mental Health Service Usage in California

Technology: Excel (Power Query), Power BI

Data Source: data.ca.gov (Children and Mental Health Services Usage) https://data.ca.gov/dataset/mhs-dashboard-children-and-youth-demographic-datasets-and-report-tool/resource/ef40bfa1-f810-4dcb-8015-c410d84b245c

Description: In July 2022, the Biden-Harris administration released a statement regarding a solution to the “youth mental health crisis” in which they announced two actions to strengthen school based mental health services and address the crisis. They included:

“1. Awarding the first of nearly $300 million the President secured through the FY2022 bipartisan omnibus agreement to expand access to mental health services in schools. 

2. Encouraging Governors to Invest More in School-Based Mental Health Services.” (whitehouse.gov). 

As a former mental health educator who has worked with high school youth, this topic is important to me because I have witnessed first hand what this mental health crisis looks like and how the demand for mental health services in schools is overwhelmingly higher than what is currently being offered. I chose a dataset from data.ca.gov based on youth mental health service usage from 2018 to 2021.. The data comes from medi-cal service records and spans all of the counties in California, as well as providing data on race, fiscal year, and the type of services provided. The dataset also 

Goal: My goal with this dashboard is to bring forth a visualization of recent youth usage of mental health services in California and identify which population is using the most mental health services, as well breaking down service usage by county. I also wanted to identify the total amount of money spent on mental health services and the total number of youth who have benefitted from the services.

Process: I downloaded the data and used excel power query to clean and manipulate the data. I removed extra columns, replaced abbreviations used in the data to full names, and filtered out unnecessary data points in my analysis. The ‘population’ column was particularly challenging because alongside the California counties, there were other subsets of the counties based on medical providers and other combinations of counties. I ultimately decided to only keep the county-based totals in the population column. After cleaning, I imported the excel file to Power Bi and created two cards that display the total money spent on mental health services statewide and the total number of beneficiaries from 2018 to 2021. I also made two multirow cards showing the amount of dollars spent on services per county and the percent of beneficiaries broken down per county. Finally, I created a clustered column chart to show the total number of beneficiaries broken down by race, along with year and population slicers to filter for a particular year or county. 

Results: 

California spent a total of 7.92 billion dollars in mental health services between 2018 and 2021. Also within that time frame, 2.19 million youth used mental health services. Hispanic, White, and Black youth used the most mental health services. Los Angeles, Santa Clara, Alemeda, San Bernardino, and San Diego spend the most on mental health services, while Los Angeles, San Bernardino, San Diego, Orange, and Riverside accounted for the most beneficiaries coming from those counties. The number of beneficiaries seemed to decrease after 2019, which would account for COVID lockdown; though, further research would be needed to add more context for the drop in beneficiaries. The consistently high number of Hispanic youth as mental health service beneficiaries would also warrant further study and analysis with a greater sample size to see if the same patterns are seen in Hispanic youth across other states. Given that the Biden-Harris administration have launched their initiative to increase funding and availability of mental health services in schools after the time-span of this data, it would be prudent to conduct another survey and analysis to see the impact of the changes stated in the initiative. In my professional experience, one of the main concerns of students is their privacy of using mental health services and not wanting to involve their parents in the process. The Biden-Harris school mental health initiative potentially addresses this issue by increasing the availability of the mental health services in school, and I would predict that the numbers of youth using mental health services would increase given the ease of accessibility. 

![image](https://github.com/carlosroman9/California_Youth_Mental_Health_Service_Usage/blob/main/Youth_Mental%20Health%20Usage_2021.jpg?raw=true)

