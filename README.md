# Covid-Analysis
Dataset link: https://ourworldindata.org/covid-deaths

## Data preprocessing:

We are preprocessing the data using python in jupyter notebook. Here we will be cleaning our dataset like removing unnecessary data. we will create two separate files for "Covid Vaccination" and "Covid Deaths".

Then we have removed unnecessary columns and created a checkpoint. We have also reordered our column value for ease of access.

Then we created two copies of naming 'CovidDeaths' and 'CovidVaccinations' and exported as excel files.


## SQL Queries:

We have created a new database in SQL and uploaded those two files we exported during data preprocessing. We have used following method in our queries:

Joins, CTE's, Temp Tables, 
Windows Functions, Aggregate Functions, Creating Views, 
Converting Data Types

We ran these following queries:
1. Select Data that we are going to be starting with
2. Total Cases vs Total Deaths
-- Shows likelihood of dying if you contract covid in your country
3. Total Cases vs Population
-- Shows what percentage of population infected with Covid
4. Countries with Highest Infection Rate compared to Population
5. Countries with Highest Death Count per Population
6. BREAKING THINGS DOWN BY CONTINENT
-- Showing contintents with the highest death count per population
7. GLOBAL NUMBERS
8. Total Population vs Vaccinations
-- Shows Percentage of Population that has recieved at least one Covid Vaccine
9. Using CTE to perform Calculation on Partition By in previous query
10. Using Temp Table to perform Calculation on Partition By in previous query
11. Creating View to store data for later visualizations


## Tableau Visualization:

lastly we have done few SQL queries for our visualization. We have saved those query output in 'Tableau visualization' folder. Used those data for our visualization.

![Tableau Dashboard](https://user-images.githubusercontent.com/106653421/172135563-13fa74cd-2cb2-4bca-b0c2-edd2dd8501af.jpg)














