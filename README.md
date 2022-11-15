# Loan-Dataset
The data used in this project is based  on loans disbursed from March 2021 to May 2021 by a lending institution. It contains information about the loans disbursed, repayment date, and demographic information about the customers obtaining these loans.

# Objective

The objective of this analysis is to gain some insights about the customers who apply for these loans, their reasons and how these loans are actually performing by calculating the portfolio at risk using PAR7 AND PAR30 ratios. 

Profitability at risk ratio is widely used by banks to determine if they have too many unpaid loans and can be used to set targets for loan risk and recovery. It is calculated as the percentage of loans repayments overdue to the total loans paid out

# Tools

Python (Numpy, Pandas and Matplotlib Libraries), Jupyter Notebook and Excel were used to conduct this analysis although Excel was only used briefly to visually access the data. Most of the analysis occurred in Jupyter Notebook using Python.

# Data Gathering

The data was obtained directly from the lending institution and permission was given to use the data for the purpose of this project.

# Data Cleaning

Since the original data set is a csv file, a lot of data type conversion had to be done to make the data ready for exploration using the pandas library. All cleaning steps are detailed in the main project file.

Most importantly, a lot of duplicated data had to be dropped. The data set contains different snapshots of the same loan(s) as at different dates. The most recent iteration of these loans(sorted by date) were used for the purpose of this analysis with all earlier iterations discarded. This was necessary to get the actual loan portfolio, balance yet to be repaid and other key metrics.

The portfolio at risk if considering only loans overdue by more than 7 days was determined to be 20.19% while those overdue by more than 30% was at 13.79%.
