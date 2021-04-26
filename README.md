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
- There are a total of 38,010 reviews, of which 170 are Vine reviews and 37840 unpaid reviews.
- There were a total of 20,677 5 star reviews, of which 65 were Vine reviews. The other 20,612 were made by non-Vine users. 
- The 0.3% of 5 star reviews were made by Vine users. Which means that 99.7% of the reviews were made by non-Vine users. 
- Of all the Vine reviews, only 38.2% were 5 starts, the other 54.5% of 5 star reviews where made by non-Vine Users.

## Summary:
Is there bias toward favorable reviews from Vine members? Considering the results of this analysis it's hard to conclude that there is any sort of bias. The amount of participation from the Vine program is too low. In the other hadn we can conclude that most reviews written by Vine users are positive where most of them are 5 star reviews. 
