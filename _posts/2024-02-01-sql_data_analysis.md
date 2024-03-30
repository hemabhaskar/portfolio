---
title: Data analysis - MySQL
layout: post
post-image: "https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/ER_diagram.png"
description: The objective is to demonstrate SQL proficiency by creating an OLAP Database for VivaK, a retail chain in Southlake, Texas, USA. Tasks include analyzing data, designing a MySQL Data Model, schema creation, data import and cleaning, and performing complex calculations. Key objectives involve handling duplicates, formatting data types, treating missing values, and calculating metrics like experience_at_VivaK and last_performance_rating. This project showcases expertise in SQL data modeling, schema creation, data cleaning, and complex calculations for real-world business analytics challenges.
tags:
- jekyll
- informative
- technology
---

The SQL project at VivaK involved importing and harmonizing diverse data formats into the 'vivakdump' schema, serving as a staging ground. Subsequently, the meticulously crafted 'vivakhr' schema was created, ensuring clean and organized data for analysis. Tasks included handling duplicates, aligning data types, and filling missing values to maintain database integrity. Refinement of columns like 'report_to' and strategic handling of missing salary entries were key highlights. Additional tasks involved calculating time differences, generating random performance ratings, and updating salary calculations. Overall, the project showcased adept data management strategies, laying the foundation for comprehensive analysis within VivaK's OLAP system.
{:target="blank"}
###### Source Code : [`Jekyll Docs`](https://jekyllrb.com/docs/)

## Key Steps and Analysis

Given the complexity of the data management at VivaK, which involved multiple formats and anomalies, a meticulous plan was devised by importing data from various sources into a schema named 'vivakdump.' This schema served as a staging ground for harmonizing data from JSON, CSV, and Excel files.

The process unfolded in three steps
##### 1. SQL File Upload<br>
 Initiated the process by uploading the SQL file (HR) containing essential data (countries, locations, and regions). This formed the foundational layer for subsequent integration.
##### 2. Importing Diverse Data Formats<br>
Systematically, have imported data from JSON (employees), CSV (dependent), and Excel (orgstructure) files into the 'vivakdump' schema. This ensured seamless coexistence of data from different sources.
##### 3. Creation of Final 'vivakhr' Schema<br>
With all data consolidated in the 'vivakdump' schema, the final 'vivakhr' schema has been created. This schema, characterized by clean and organized data, led to the well-designed OLAP database for VivaK.

### Schema Design Process
Entities:
Identify entities based on the narrative. Examples include Employees, Departments, Locations, etc.

### Attributes
List the attributes for each entity. For example, Employee attributes might include employee_id, employee_name, hire_date, etc.

### Constraints
Identify and define primary keys, not null columns, and unique keys for each entity.
Handle the "location_id" column issue in the Employees data.

### Relationships and Foreign Keys
Establish relationships between entities (e.g., Employees report to Managers).
Define foreign keys based on relationships.

### Schema Creation
The process commenced by checking for the existence of the 'vivakhr' schema. If found, it was promptly dropped to ensure a clean slate for subsequent actions. Following this, the necessary tables, including regions, countries, locations, departments, jobs, employees, and dependents, were meticulously created within the newly established 'vivakhr' schema. This systematic approach laid the foundation for a well-structured schema, facilitating comprehensive data analysis and reporting in VivaK's OLAP database.

### Import and Clean Data
Data import into the 'vivakhr' schema tables from the 'vivakdump' schema was seamlessly executed. The process encompassed addressing duplicates, aligning data with designated data types, and resolving missing values. Key actions involved standardizing phone numbers and dates, and confirming the double data type for all salary-related columns. This meticulous approach ensured the integrity and coherence of the database, laying the groundwork for robust analytics within VivaK's OLAP system.

Data Insertion into vivakhr Schema Tables:
Data insertion into tables involved careful selection of records from corresponding tables in the 'vivakdump' schema.

### Handling Missing Values
A thorough examination of the data at hand resulted in the "report_to" column in the "employees" table being refined, guaranteeing that correct managerial information was effortlessly incorporated. Additionally, a creative solution was used to solve the missing entries in the salary column which determined the mean of "min_salary" and "max_salary," offering a thorough way to guarantee accuracy and completeness of data in VivaK's OLAP system.

### Handle Duplicates
Ensured that there is no redundant data in the tables and that they are fully normalized. Use qualifying candidate keys to detect and deal with duplicates.

### Calculations and Updates

* experience_at_VivaK
Calculate the time difference (in months) between the hire date and the current date for each employee and update the column.

* last_performance_rating
Generate random performance ratings for each employee and update the column.

* salary_after_increment
Calculate and update the salary_after_increment column based on the provided formulas.

* annual_dependent_benefit
Calculate and update the annual_dependent_benefit column based on the specified rules

* Email Update
Replace employee email addresses with the new domain 'vivaK.com'.