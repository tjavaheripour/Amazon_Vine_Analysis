# Amazon_Vine_Analysis

## Overview of the analysis:

This project is about analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project I picked [a data set](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) from Amazon reviews regarding kitchen and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark and Pandas to determine if there is any bias toward favorable reviews from Vine members in this dataset. 


## Results:

- How many Vine reviews and non-Vine reviews were there?

There were 1207 total Vine reviews(paid).

![1.PNG](https://github.com/tjavaheripour/Amazon_Vine_Analysis/blob/main/Images/1.PNG)

There were 97839 total non-Vine reviews(unpaid).

![2.PNG](https://github.com/tjavaheripour/Amazon_Vine_Analysis/blob/main/Images/2.PNG)

- How many Vine reviews were 5 stars? 

![3.PNG](https://github.com/tjavaheripour/Amazon_Vine_Analysis/blob/main/Images/3.PNG)

- How many non-Vine reviews were 5 stars?

![4.PNG](https://github.com/tjavaheripour/Amazon_Vine_Analysis/blob/main/Images/4.PNG)

- What percentage of Vine reviews were 5 stars?

![5.PNG](https://github.com/tjavaheripour/Amazon_Vine_Analysis/blob/main/Images/5.PNG)

- What percentage of non-Vine reviews were 5 stars?

![6.PNG](https://github.com/tjavaheripour/Amazon_Vine_Analysis/blob/main/Images/6.PNG)

## Summary:
Based on results, we can conclude that the Percentage of Non-Vine or unpaid reviews that received 5-Stars was actually more than the paid reviews so paying for the Vine service to get paid reviews does not necessarily provide a positivity bias that results in more 5-Star reviews.
one additional analysis that we could do with the dataset is to find the rating for each star (1-5) for vine and non-vine reviews and compare them. Additionally we could divide a dataset in two sections as positive and negative reviews of paid and unpaid program and analyze the results. 
