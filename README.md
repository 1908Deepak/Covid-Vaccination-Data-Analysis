# COVID VACCINATION DATA ANALYSIS 💉🌍

### Dashboard Link :https://app.powerbi.com/links/Gl1GZMHFWZ?ctid=37d002c9-062c-435d-beff-d1efc9989fe4&pbi_source=linkShare

## Problem Statement

COVID-19 Vaccination Data Analysis Dashboard – Power BI

This dashboard provides insights into vaccination progress across countries, showing the number of people vaccinated, fully vaccinated, and total vaccinations.
By tracking vaccination trends over time, it helps governments, organizations, and analysts measure vaccination drives’ impact globally. type and region.

## Key Objective

To create a single interactive dashboard for monitoring vaccination performance, comparing vaccination progress across countries, and analyzing vaccination patterns over time.


### Steps followed 

Step 1 – Load Data from CSV File

- Used Get Data → Text/CSV option in Power BI Desktop.


Step 2: Open Power Query Editor and in the View tab under Data Preview, enabled:

- Enabled:

  - Column distribution

  - Column quality

  - Column profile

- Set profiling to "Based on entire dataset".

Also, changed profiling to “Based on entire dataset”.

Step 3 – Data Quality Checks

- Checked for null values in Country, People Vaccinated, Vaccines.

- Date fields formatted properly to enable Year/Month slicers


Step 5 : KPIs
Created card visuals with DAX measures:

        Total Countries = DISTINCTCOUNT(CovidData[Country])

        People Fully Vaccinated = SUM(CovidData[People_fully_vaccinated])

        Total Vaccinations = SUM(CovidData[Total_vaccinations])

![KPIs](https://github.com/user-attachments/assets/1a1a6432-ccb6-454e-b7e9-e926b866fed4)


Step 5 – Slicers Added

- Year
- Month

Step 8 - Publish to Power BI Service 
- Published dashboard for cloud access and sharing with stakeholders.


![Publish_Message](https://github.com/user-attachments/assets/1722d74e-2f75-4869-b109-8bc76f0de14d)

# Dashboard :   Index Page 

![dashboard_snapo](https://github.com/user-attachments/assets/c7d47d1a-7274-498b-ba4e-1e344bde1752)

 
 
# Insights

### Global Trends

- Countries show varying vaccination progress – some reaching 70%+ fully vaccinated, while others lag.

- Vaccination rollouts spiked during early 2021–2022, then stabilized

### By Country

- Developing nations show slower adoption rates.
- Countries like USA, India, UK dominate total vaccinations.

# Conclusion

The COVID Vaccination Dashboard enables:

- Tracking global and country-level vaccination progress

- Analyzing trends across years and month

- Supporting governments and organizations in understanding vaccination gaps


   
## Resources

[Vaccination Dataset](https://drive.google.com/file/d/1h2v2--0-v8EZ0pz7DTSdk4odyGJBJFFK/view?usp=sharing)



## Authors

- [1908Deepak](https://github.com/1908Deepak)


## Feedback

If you have any feedback, please reach out to us at deepaksingh190810@gmail.com

