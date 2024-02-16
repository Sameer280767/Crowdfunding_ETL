# Crowdfunding_ETL

## Introduction

3 functions were performed in this project.
Extract: 
1. Data was extracted from 2 Excel files. First file contained crowd funding data. 2nd file contained contact information

Trasform:
1. Excel files were converted to Pandas DataFrames and manipulated
2. Dataframes were then merged
3. 2 options were demonstrated as part of data transformation. One using Pandas DataFrames and JSON and the oher using REGEX

Load:
1. 2 Excel files were now converted to 4 csv files and loaded into a database and 4 tables created
2. Tables were populated using csv files generated from transform methodology as detailed above
3. Care was taken to populate the table in order of contacts, categoy, sub category and campaign. This was due to constraints (foreign keys) defined for campaign table
2. Using sql queries the tables were linked with primary and foreign keys
3. Entity Relationship Diagram (ERD) of the tables was created to provide a visual representation of the database structure
2. We now had the capability to analyse data

## Sources of data

Within Resources Folder:
*  contacts.xlsx
*  crowdfunding.xlsx

## Database Type for Final Production Environment

* Database Type: Relational (SQL)
* Data Cleaning and Processing: Jupyter Notebook
* Packages Used: pandas, numpy, datetime
* Data Loading: pgAdmin

# Project Outline

## Summary of steps undertaken

* Create the Category and Subcategory DataFrames
* Create the Campaign DataFrame
* Create the Contacts DataFrame
* Create the Crowdfunding Database with table stucture using primary and foreign keys

