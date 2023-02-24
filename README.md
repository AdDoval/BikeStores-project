# This is a follow along proyect in SQL, excel and Tableau. 

The objective of this project is to get familiarized with SQL and tableau.

## 1.- Loading the data

First we execute the queries obtained from the tutorial:  
    1. Creating objects with **"BikeStores Sample Database - create objects.sql"**.  
    2. Populating objects with data provided in **"BikeStores Sample Database - load data.sql"**.

These queries are avaliable in the "Initial data and set up" folder.  
## 2.- Creating usable data frame

Now that we have al the tables with the corresponding data, we need to query the data that we need to do the analysis.  
  
![SQL query](img/SQL%20query.PNG)

## 3.- Importing data into excel

Our manager has requested a dashboard containing all available data to conduct their own analysis. Excel enables us to generate a dashboard and share it with our manager, along with the data. Meanwhile, Tableau will be utilized to create a more polished dashboard to present during the board meeting.

To avoid using outdated data in the future, we connect Excel to a SQL server to directly load the queried data.

Once we have our data in excel we check if all the colums and rows have been imported and if there are any possible errors.

## 4.- Creating the dashboard in excel

We start by creating all the needed pivot tables that will act as data source four our charts.

Pivot tables can the ability to share cache and grouping settings, leading to unintended changes in one table when adjusting another. To prevent this, we create a second pivot table using the PivotTable Wizard, which enables the use of two separate caches for our pivot tables. This was the case for our "Total revenue" and "Revenue per month" charts.

Once we have create all the pivot tables need we start inserting all the charts in our dashboard. Having the dashboard set up we provide a set of slicers for our managers to filter the data.

Here we can see how the dashboard looks:
![Screen capture dashboard 1](img/excel%20dashboard_1.PNG)
![Screen capture dashboard 2](img/excel%20dashboard_2.PNG)

## 5.- Creating the dashboard in tableau