# Amazon Vine Analysis

## Overview
PySpark, AWS, and Postgres were used to analyze Amazon reviews for Office Products to determine if reviews from Amazon Vine members are biased.
The Office Products dataset was chosen from Amazon and an analysis was conducted using PySpark to perform the ETL process, connect to an AWS RDS instance, and to load the transformed data into pgAdmin. PySpark was also used to analyze the dataset and determine the bias towards favorable reviews from Amazon Vine members.


## Results

### In the Amazon Office Products Reviews dataset:

* **969** reviews were from Amazon Vine members
* **43,745** reviews were not from Amazon Vine members
![vine_reviews](https://user-images.githubusercontent.com/64225504/139511176-dac3aee8-2839-4e7d-8226-ea85498d90d3.png)




* Of the 969 reviews from Amazon Vine members, there were **430** 5-star reviews
* Of the 43,745 reviews not from Amazon Vine members, there were **19** 5-star reviews
![five_star_reviews](https://user-images.githubusercontent.com/64225504/139511185-47cf5642-d9a9-4bfe-a092-60f435d66d5f.png)



* **44%** of reviews by Amazon Vine members were 5 stars 
* **44%** of reviews not by Amazon Vine members were 5 stars
![five_star_percentage](https://user-images.githubusercontent.com/64225504/139511196-f87a1402-0bc7-4a08-bd5e-967cdc975698.png)




## Summary
Comparing the percentage of reviews that were 5 stars from both Amazon Vine members and not Amazon Vine members, it can be concluded that there is no positivity bias for reviews of Office Products in the Vine program. The percentage of five-star reviews from both groups are nearly the same, rounded to 44%. A similar analysis could be conducted to compare the one-star or low reviews from both Vine and non-Vine members to further support this conclusion.
