# Data cleaning of global mass layoff dataset
This project aims to mimic some of the data related work I did as an individual contributing product manager at my last organisation.

Process before my arrival at the company:
- Data science team downloads data from database
- Send the data to data science team for data cleaning & standardisation
- Data forwarded to business analyst or product analyst
- Analyst makes dashbaords, runs script, does analysis, reports insights.
- Insights report handover to product managers and senior management
- Management makes product decisions based on the insights

Process after my arrival:
- I download the data myself with restricted acces to the database
- Clean the data myself using just MySQL & Python whenever required ( THIS PROJECT COVERS THIS STEP )
- Leveraged GenAI to run complex queries & scripts that are out of my expertise.
- Conduct sanatisation checks.
- Handover data to analyst for integration and collaborate with analyst for analysis.
- Create reports myself and shared with stakeholders.
- Took key product decisions based on insights in the report.

Outcomes:
- Reduced time to conduct ad-hoc exploratory analysis by 20%
- Reduced time shipping time (product changes, features, new builds) by 15% 
- Got first hand insights of our customer data which helped in making robust management decisons.

In this project, I have taken the layoff data of various companies accross the globe during covid. This dataset is very rich and is similar to the type of data I worked with in my previous company.
I clean the data to make it ready for exploratory analysis. 
Goals:
- Create a staging table to avoid unwanted changes
- Delete duplicates
- Delete unwanted values
- Standardise data

