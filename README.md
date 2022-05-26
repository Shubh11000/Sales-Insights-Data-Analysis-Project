# Busiess Sales Insight Dashboard

## Problem Statement

A Delhi-based computer hardware manufacturing company AltiQ, sales have declined recently, and the head sales director wants to identify where the business is failing. So I have build a dashboard that provides business insight to perform data driven-decision to maximize company profit.

## Approach

### Business Understanding

Before venturing into the project, the AIMS grid was used for planning and laying the foundation for successful implementation.

<p align="center">
<img src="https://github.com/Shubh11000/Sales-Insights-Data-Analysis-Project/blob/main/aims_grid.PNG">
</p>

### Data Engineering Cycle

<p align="center">
<img src="https://github.com/Shubh11000/Sales-Insights-Data-Analysis-Project/blob/main/Data%20Lifecycle.png">
</p>

Usually, in such scenarios data from the data source such as OLTP are transformed using the ETL process before it gets loaded to a Data Warehouse, which is then connected to a BI tool to carry out the analysis.

For our case study, we have used a Power BI for data analysis that has a live connection with a MySQL data source.

<p align="center">
<img src="https://github.com/Shubh11000/Sales-Insights-Data-Analysis-Project/blob/main/Star_schema.png"><br>Fig:Database Schema
</p>


