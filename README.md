# Amazon_Vine_Analysis

## Overview of the analysis:

This project is about analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project I picked [a data set](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) from Amazon reviews regarding kitchen and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark and Pandas to determine if there is any bias toward favorable reviews from Vine members in this dataset. 


## Results:
