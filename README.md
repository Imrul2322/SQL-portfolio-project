# Data Exploration, Cleaning, Visualization and Correlation

## Key Findings

USA was one of the biggest victim of COVID-19 in terms of COVID-19 cases, death counts. From visualization first and second wave of COVID-19 in US can be observed clearly. Total death count was highest in Europe among continents. Vaccinations started in USA on December 2020 and by May 2022, 66.65% people were fully vaccinated. Most of the countries in Africa, were in shortage of vaccine, vaccination rate is very low. Though China was the source of COVID-19, impact was very low in China, where USA was the biggest victim.

## Table of Contents

* <a href="https://github.com/Imrul2322/Data-Cleaning-Explroration-and-Visualization#Resources">Resources</a>
* <a href="https://github.com/Imrul2322/Data-Cleaning-Explroration-and-Visualization#Dataset">Dataset</a>
* <a href="https://github.com/Imrul2322/Data-Cleaning-Explroration-and-Visualization#Data-Exploration-SQL">Data Exploration SQL</a>
* <a href="https://github.com/Imrul2322/Data-Cleaning-Explroration-and-Visualization#Data-Visualization-in-Tableau">Data Visualization in Tableau</a>
* <a href="https://github.com/Imrul2322/Data-Cleaning-Explroration-and-Visualization#Data-Cleaning-in-SQL">Data Cleaning in SQL</a>
* <a href="https://github.com/Imrul2322/Data-Cleaning-Explroration-and-Visualization#Data-Correlation-using-Python">Data Correlation using Python</a>

## Resources

* Microsoft SQL Server Management Studio
* Google Cloud Services (Cloud SQL)
* Tableau
* Python (Pandas)

## Dataset

Data collected from https://www.worldometers.info/coronavirus/

Modified 1: https://drive.google.com/file/d/1nW08bdKSjJqNtVC53bY07q1X-1Cof4Sg/view?usp=sharing

Modified 2: https://drive.google.com/file/d/1qR1Gt9YQGRzrQzRpeFD7QTunRsfoRMst/view?usp=sharing


## Data Exploration SQL 

* Created queries using sub-queries, partitions, join, CTE, temp table, window function etc. 
* Extracted information regarding COVID-19 deaths, cases and vaccinations across the world. 
* Countries affected most in COVID-19 and countries were fast to respond with vaccination. 
* Information in both country and continent wise. 

## Data Visualization in Tableau

Information provided:
* Global vaccination count and percentage.
* Countries which had less than 10% vaccination rate.
* Countries which are impacted most due to COVID-19.
* Comparision between US and China on COVID-19 impact.

for interactive dashboard, click <a href="https://public.tableau.com/views/GlobalCovid-19DeathandVacc_Report/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link">here</a>

![step 0](https://github.com/Imrul2322/Data-Cleaning-Explroration-and-Visualization/blob/main/global%20vaccination%20report%20tableau.png "title")

## 3. Data Cleaning in SQL

* Changed the date format to 'yyy-MM-dd' format.
* Split complete location address to street address, city, state and zip code (substring & parsename). 
* Brought consistency in data (e.g. ('Y', 'Yes') to 'Yes').  
* Handled duplicate rows and remove irrelevant columns. 

Dataset: https://docs.google.com/spreadsheets/d/1c8IQveix6Ly5pPAezQ0xaGoSh3ObXuxC/edit?usp=sharing&ouid=112644935180655994459&rtpof=true&sd=true

## Data Correlation using Python

* Replaced missing values with zero.
* Fixed data type of numerical value columns. 
* Dropped duplicate columns.
* Unstacked data to find highest correlated features in the data. 

Dataset: https://drive.google.com/file/d/1K9RORIgg2pmFeM3OAtv-ShMifi4CQg3x/view?usp=sharing
