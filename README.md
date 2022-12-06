# final_project_cis9440
NYC affordable housing transparency project
author(s): Dajana Avxhi, Diego Mora Rojas, Amanda Maglaras, Mingxing (Max) Lin
date created: 11/27/2022
class: CIS 9440
Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools: The tools used to build this Data Warehouse were: 1. For data integration - python 2. For data warehousing - Google BigQuery 3. For Business Intelligence - Tableau

Kimball Lifecycle Project Stages
Project Planning
Motivation for project: Considering the fact that affordable housing in general is a persisting issue in NYC and combining that with the post COVID financial situation of many, we wanted to learn more and share some information which can be helpful for people looking into housing or people looking to start a project. We wanted to shed some light into the locations of current housing projects and affordability based on median income, mainly focusing on low income units. Additionally, this project aims to find out how many of the tax abatements given to developers are being translated to actual affordable housing units each year.

Description of the issues or opportunities the project will address: The project will help provide information regarding locations, construction, the type of units and more on housing projects that are part of Housing New York or Housing Our Neighbors plan. Since rent and housing affordability in general is such a huge issue in NYC, this project will help to determine how many of these buildings getting tax incentives are being constructed and/or completed each year and how many are affordable by those with low income. Additionally, it will also provide information on what the affordability looks like for each building which can be useful when looking for a unit to rent.

Project Business or Organization Value: NYC residents, government watch groups and policy makers can get transparent information on the city afforda Ji ble housing initiatives. Real estate management companies can use this information as a research tool to help manage their projects.In addition, construction companies and people looking to invest can understand the volume and type of business affordable housing can bring.

Data Sources: 
1. https://data.cityofnewyork.us/Housing-Development/Affordable-Housing-Production-by-Building/hg8x-zxpr 
2. https://data.cityofnewyork.us/Housing-Development/Local-Law-44-Tax-Incentive/72vt-ykjc ...

Business Requirements Definition
List of Data Warehouse KPI's:
1. Total number of affordable housing projects started by year
2. Total number of affordable housing projects completed by year 
3. Total Tax Abatements given by year 
4. Count of affordable housing units for rent by building 
5. Count of extremely low to low-income units by location ...

Dimensional Model
This project's Dimensional Model consists of 3 Facts and 3 Dimensions

![Alt text](Dimensional_Model.JPG)


This project's Kimball Bus Matrix:
![Alt text](Kimball_bus_Matrix.JPG)

Business Intelligence Design and Development
List of Visualizations for each KPI: 
1. Stacked bars for comparison of number of projects started each year 
2. Stacked bars for comparison of number of projects completed each year 
3. Heat map for a contribution analysis of incentives given each year by borough and percentage
4. A geography map for analysis of count of units for rent in each building and their location 
5. A geography map for analysis of count of extremely low to low income in each building and their location ...

BI Application Wireframe design:
![Alt text](wireframe.JPG)


Picture of final Dashboard:

![Alt text](Dashboard_KPIs.PNG)

Deployment
The project was deployed on Tableau Public: https://public.tableau.com/app/profile/diego.mora.rojas/viz/KPIsVisuals/Dashboard1?publish=yes

