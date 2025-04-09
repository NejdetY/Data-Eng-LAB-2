# Data-Eng-LAB-2

Azure Synapse Analytics – Querying Files Using Serverless SQL Pool

This repository contains the work I completed as part of the Microsoft Learn interactive lab titled “Query data in a file using serverless SQL pool in Azure Synapse Analytics”. In this lab, I used the serverless SQL pool feature in Azure Synapse Analytics to query structured files stored in a data lake without moving the data or importing it into a database.


🎯 Purpose of the Project

The main goal of this lab is to demonstrate how to perform data analysis directly on files stored in a data lake using serverless SQL capabilities. This method allows for cost-efficient and time-saving analytics without the need to first load the data into a traditional database system.


🧩 Steps Performed

1-Creating an Azure Synapse Workspace

A new Synapse workspace was created via the Azure portal.

2-Preparing the Data Lake

Sample CSV files provided by Microsoft were uploaded to an Azure Data Lake Storage account.

3-Creating a Database in Serverless SQL Pool

A new database named Sales was created using the serverless SQL pool.

4-Defining an External Data Source (EXTERNAL DATA SOURCE)

An external data source was created to connect the database to the files stored in the data lake.

5-Defining File Format (EXTERNAL FILE FORMAT)

A file format definition was created to match the structure of the CSV files.

6-Creating an External Table (EXTERNAL TABLE)

An external table was created to represent the file. This allowed SQL queries to be executed on it as if it were a regular table.

7-Querying and Validation

Data was queried using SELECT statements and the results were validated to ensure correctness.


🖼 Screenshots

Each step of the lab is documented with screenshots, organized into folders in this repository. These visuals serve both as a reference and a guide for others who want to follow the same lab steps.


📌 Notes

This lab can be reproduced by anyone with access to an Azure subscription.

Serverless SQL pools enable querying data without moving it into a database.

It is a valuable learning resource for those interested in data engineering and big data analytics.
