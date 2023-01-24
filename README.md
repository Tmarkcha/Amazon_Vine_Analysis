# Amazon_Vine_Analysis

## Overview

The purpose of this project was to pick a dataset of interest from Amazon and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Aftewards, PySpark is used to determine if there is any bias toward favourable reviews from Vine members in the dataset. The dataset in this project pertains to video games, as they are of much interest.

## Results

- How many Vine reviews and non-Vine reviews are there?
  - There was a total of 4,291 reviews that were from Vine users, and another 1,781,706 reviews from non-Vine users in the unfiltered dataset.
  
  ![Result1](https://user-images.githubusercontent.com/111096246/214439271-16e75c5c-5d01-4e22-8bbf-858c0a86c274.PNG)
  
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There was a total of 48 reviews that were five stars, by Vine users. On the other hand, there were 15,663 five star reviews by non-Vine users.
  
  ![Result2](https://user-images.githubusercontent.com/111096246/214445355-09330e6c-a86f-42cd-ae67-ca6f0c8b8f15.PNG)
  
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 51.1% of five star reviews were Vine users, and 38.7% were not Vine users.
  
  ![Result3](https://user-images.githubusercontent.com/111096246/214446187-8d4af4d5-77d8-462f-971a-c823e897d284.PNG)

## Summary

After conducting analysis there appears to be a bias from Vine users, as there is a 12.4% difference between Vine users and non-Vine users who gave out five star ratings. The bit of bias might be due to the fact that, potentially, some Vine users do not want to put in the effort to rate the purchase, so they provide an arbitrary five stars, as the product may meet their expectation.
