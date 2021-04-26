# Amazon_Vine_Analysis
## Overview of the Project

In this project we analysed Amazon reviews written by members of the paid service [Amazon Vine program](https://www.amazon.com/gp/vine/help). I performed the ETL process to extract the dataset, transform the data, connect to an Amazon Web Services instance and finally loaded the transformed data into pgAdmin. Then we used Pandas to determine if there is any bias toward favorable reviews from Vine members in the dataset. 

__Tools:__ 
- pgAdmin v5
- PySpark 3.1.1
- Amazon RDS

__Datasets:__
- [Amazon pet products dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz)

## Results:
- There are a total of 38,010 reviews, of which 170 or 38.2% are Vine reviews and 37840 or 54.5% unpaid reviews.
- There were a total of 20,677 5 star reviews, of which 65 were Vine reviews, meaning the 0.3%. The other 20,612 or 99.7% were made by non-Vine users. 

## Summary:
