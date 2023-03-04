# Top-100-Hotels-Report

## Introduction
A report of the top 100 hotels from [Travel+Leisure](https://www.travelandleisure.com)
This report uses survey information from Travel+Leisure. It is based on the 2021 survey information. There is a plan to update the report as the 2022 report is now out. But I would like to keep the 2021 information so I can show the change in rating from 2021 to 2022. I will need to rework the tables and store the year to show the rank from the previous year to the rank for the current year. 

### Dataset 
The dataset was downloaded from Kaggle. 
I took the opportunity to create a star schema by creating lookup tables for the owning company and for the location and hotel theme. I was then able to add index columns to the data table and remove the text column from the data table. Therefore reducing its size. I then created the relationships in the model view in Power BI Desktop.

### Future Plans
I would like to rework the look of the report as it is very plain. I was testing the use of PowerPoint to create canvas backgrounds to save Power BI having to generate all the background elements such as shapes enclosing visuals. I find the current wallpaper bland and the report does not look visually interesting. 
