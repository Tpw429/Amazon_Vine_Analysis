# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program
In this project, I had access to approximately 50 datasets. Each one contained reviews of a specific products, from clothing apparel to wireless products. I had to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset. A summary of the analysis is shown below.

* How many Vine reviews and non-Vine reviews were there?
    * Paid Vine Reviews: 1,207 reviews.

    ![PaidAll.PNG](Resources/PaidAll.PNG)

    * Non-Vine Reviews: 97,839 reviews.
    
    ![UnpaidAll.PNG](Resources/UnpaidAll.PNG)


* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    * Paid Vine 5 star Reviews: 509 reviews.
    
    ![UnpaidAll.PNG](Resources/UnpaidAll.PNG)
    
    * Non-Vine 5 star Reviews: 45,858 reviews.
    
    ![UnpaidAll.PNG](Resources/UnpaidAll.PNG)
    
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    * Percentage of Vine 5 star Reviews: ~ 42.17%
    
    ![UnpaidAll.PNG](Resources/UnpaidAll.PNG)
    
    * Percentage of non-Vine 5 star Reviews: ~ 46.87%
    
    ![UnpaidAll.PNG](Resources/UnpaidAll.PNG)

## Summary

