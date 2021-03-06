# 9440 Final Project
- author(s): Hao Zheng, Shukman Lam, Peisi Zhou
- date created: 12/5/2021
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: 
1. For data integration - Google Codelab
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:
Our group was interested in learning about how Covid and what actions can be done to minimize the damage from its impact.

Description of the issues or opportunities the project will address:
Covid has taken lives away and break families apart. We wanted to slow the spread by understanding the trend of how Covid spreads.


Project Business or Organization Value:
This project addresses the Covid trends in terms of geographic impact and its impact in different month.
This insight prepares the policy makers to design policies with focus regarding to the trends.

Data Sources:
1. covid_racial_data_tracker
2. state_testing_and_outcomes
3. state_level_current_outbreak_long_term_care


### Business Requirements Definition

List of Data Warehouse KPI's:
1. Total Posiive Increase by Month
2. Death Total & Case Total By Month
3. Total Number of Current Hospitalized Patient for Top 3 States
4. Case Total & Death Total by States 
5. Death Total & Case Total by State and Month


### Dimensional Model

![image](https://user-images.githubusercontent.com/95451679/144943519-9a85f092-eac0-46e6-a098-e91ea9bf10f5.png)



This project's Kimball Bus Matrix:


![image](https://user-images.githubusercontent.com/95451679/144943181-40affb36-3e6d-4751-8b01-5431ecbb7360.png)


### ETL Steps
1. Establish BigQuery Connection
2. Extract data sources from BigQuery
3. Perform data profiling 
4. Perform data cleansing
5. Perform data integration 
6. Create Dimension table
7. Create Fact table
8. Load tables into BigQuery

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Heat Map - Total Posiive Increase by Month
2. Line Chart - Death Total & Case Total By Month
3. Bar Chart - Total Number of Current Hospitalized Patient for Top 3 States
4. Map - Case Total & Death Total by States 
5. Animation - Death Total & Case Total by State and Month

BI Application Wireframe design:
![image](https://user-images.githubusercontent.com/95451679/144768147-4608806a-d4c6-4843-9f9f-48e66f56184d.png)

Picture of final Dashboard:

![image](https://user-images.githubusercontent.com/95451679/144768181-3ad3241b-2e17-41fd-8737-e5d546eea126.png)



### Deployment

The project was deployed on Tableau Public: https://public.tableau.com/app/profile/shuk.man.lam3958/viz/COVID-19AnalysisDashboard_16383810960450/Story1?publish=yes 
