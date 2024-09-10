# Project Work Journal

This journal tracks the progress, challenges, and decisions made throughout the project. It serves as a detailed record of the steps taken and the insights gained during the analysis.

## Project Setup

I set up the project, installed necessary dependencies, and successfully loaded the data.

## Exploratory Data Analysis (EDA)

### Initial Exploration of IPUMS Data

I began by exploring the **IPUMS USA** data extract to understand its structure and variables. Initially, I wasn’t sure how to interpret the multiple identical rows in the dataset. After searching online for similar IPUMS data issues and reviewing the documentation, I found that the duplicates were fully identical, with the same **SERIAL**, **SAMPLE**, and **household weights (`HHWT`)**. I concluded that these duplicates were unintentional and could be safely removed without statistical implications.

By removing the redundant rows, I ensured the dataset reflects accurate household counts and that my analysis won’t be inflated. I also reviewed key variables like **HHINCOME** and **MORTAMT1**, which will help analyze household financial health and mortgage trends.

Next, I’ll proceed with cleaning the data and preparing it for further analysis.
