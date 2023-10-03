# LinkedIn Data Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools and Tecniques](#tools-and-techniques)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [Limitation](#limitations)
- [References](#references) 

### Project Overview
This project analyzes data from LinkedIn to extract insights about user demographics, job trends, connections, companies, invitation sent, invitation received, reactions and other relevant topics.

### Data Source
The data for this project was collected from the LinkedIn Private Data.

### Tools and Techniques
- Excel for data cleaning and manipulation
- PostgreSQL for data analysis
- Power BI for data visualization and creating report

### Data preparation 

The preparation phase , i performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis
- what is the total connection by month
- what is the total connection by company
- what is the total connection by position
- what is the total number of connection
- what is the total numner of companies
- what is the total number of messages sent 
- what is the total number of messages received 
- what is the total number of reactions
- total reaction by type of reaction

### Data Analysis
This include some codes using PostgreSQL

```sql
SELECT count(connection) AS connections
FROM DB_Linkedin;

```

### Results

The following insights were extracted from the data:
1. Total connection was higher in the month of August and low in december.
2. A total of 435 (30.68%) messages was sent and 983 (69.32%) messages was received.
3. A toal of 28 invitation was to sent while 205 was received.
4. Total reaction is 88.
5. 284 connections was made.
6. 222 companies were contacted.
7. The most position by connection is Data analysis.

### Conclusion

The results of this project provide valuable insights into the LinkedIn usage. These insights can be used by to develop and imporve engagements, traffic more effective marketing and job search strategies.

### Limitations

i had to delete unwanted columns ,null cells that would have affected my analysis.

### References 

1. SQL for Data Analysis
2. [youtube](https://www.youtube.com/results?search_query=alex+the+analyst)
3. 





