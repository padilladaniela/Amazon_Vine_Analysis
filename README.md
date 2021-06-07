# Amazon_Vine_Analysis

## Overview of the Analysis

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.


## Results
- The Table_check.png shows that the data was succesfully loaded into pgAdmin.

![Summary](https://github.com/padilladaniela/Amazon_Vine_Analysis/blob/main/Table_check.png)

![paid]https://github.com/padilladaniela/Amazon_Vine_Analysis/blob/main/paid_reviews.png

![unpaid]https://github.com/padilladaniela/Amazon_Vine_Analysis/blob/main/unpaid_reviews.png

## Summary

- 36% of the reviews in the Vine program were 5 stars reviews, however, the percentage in the non-Vine reviews is 47%. This describes a negative bias for reviews in the Vine program.
- Digital Video Game Reviews may have fewer reviews per product title so combining the data set with the Video Game Reviews dataset (which is the physical edition of the product) may offer different results for the number of review and participates in the Amazon Vine Program.
