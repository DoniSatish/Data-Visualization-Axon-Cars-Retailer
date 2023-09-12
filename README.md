# AXON CAR RETAILER

## Introduction

In today's data-driven business landscape, companies of all sizes rely on effective data management and analysis to make informed decisions. For Axon, a small retailer specializing in classic cars, managing and analysing their sales data has become a significant challenge. The absence of a centralized system has hindered their ability to gain meaningful insights from their sales data, impacting their sales team's performance and overall decision-making process.

To address these challenges, Axon has embarked on implementing a robust Business Intelligence (BI) solution. This solution leverages the power of Microsoft Power BI and SQL to efficiently manage and analyse sales data.

The primary objective of this project is to design and implement a BI solution that empowers Axon, by providing user-friendly tools and delivering valuable insights, this project aims to empower Axon to improve its decision-making process and, ultimately, enhance its sales performance.

## Database Description

The MySQL sample database schema for this project includes eight tables:

| Table Name	| Column Names | Row Count | Description |
| ------------|--------------|-----------|-------------|
| Customers | a.	Customer number <br>b. Customer first name <br>c.	Customer last name <br>d.	Address <br>e.	City <br>f.	Country <br>g.	Sales rep employee number <br>h.	Credit limit	| 122 | Contains customer data, providing insights into Axon's client base. |
| Employees	| a.	Employee number <br>b.	Employee first name <br>c.	Employee last name <br>d.	Office code <br>e.	Reports to <br>f.	Job title	| 23 | Stores comprehensive employee information, including the organizational hierarchy. | 
| Offices | a.	Office code <br>b.	City <br>c.	Country <br>d.	Territory	| 07 | Contains data related to sales office locations, contributing to sales operations management. |
| Order Details	| a.	Order Number <br>b.	Product code <br>c.	Quantity Ordered <br>d.	Price each	| 2996 | Contains detailed information about the line items within each sales order. |
| Orders	| a.	Order number <br>b.	Order Date <br>c.	Required Date <br>d.	Shipped Date <br>e.	Status <br>f.	Customer Number	| 326 | Captures sales orders placed by customers. |
| Payments | a.	Customer number <br>b.	Payment date  <br>c.	Amount	| 273 | Records payments made by customers, helping track financial transactions. |
| Product lines |  a.	Product line <br>b.	Product Description	| 07 | Categorizes products into different product line categories. |
| Products | a.	Product code <br>b.	Product Name <br>c.	Product line <br>d.	Product scale <br>e.	Product vendor <br>f.	Quantity in stock <br>g.	Buy price <br>h.	MSRP | 110 | Stores a list of scale model cars available for sale. |

This database schema serves as the foundation for the project, allowing for the extraction, transformation, and analysis of sales data to meet Axon's objectives effectively.

## Methodology

•	**Data Collection:** Data Collection is the initial step in gathering and quantifying information on specific variables within an established system. It serves as the foundation for answering pertinent questions and assessing outcomes.

•	**Data Storage:** The data is efficiently stored and managed using the MySQL database management system.

•	**Data Cleaning:** An imperative phase after data storage, involves the thorough cleansing and transformation of data. This process is pivotal for ensuring the data's quality, which, in turn, impacts the quality of subsequent visualizations and reporting. Meticulous data cleaning and transformation are essential to create accurate and reliable visualizations.

•	**Data Analysis:** Data Analysis comprises a series of actions, including inspection, cleaning, transformation, and modelling of data. The primary objective is to unearth valuable insights, draw conclusions, and support informed decision-making.

•	**Visualization:** Visualization is the art of converting raw data into visual representations. This process entails the manual transformation of data into charts, graphs, and various other visual formats. The objective is to present collected data visually, aiding in its interpretation and comprehension.

