# Amazon_Vine_Analysis

## Overview of Analysis
The purpose of this analysis is to compare Vine (paid) reviews to non-Vine (not paid) reviews for Amazon Musical Instruments products. This analysis will take the Amazon review dataset located in an S3 bucket, create different tables with that data, add those tables to Postrgres, and compare the Vine reviews to the non-Vine reviews using PySpark and Google Colab.

## Results

### Total Reviews: 

- Vine: ![image](https://user-images.githubusercontent.com/102273449/185757819-980b8de3-75ec-4f63-bad2-76ed93d7e5f8.png)
  
- Non-Vine: ![image](https://user-images.githubusercontent.com/102273449/185757861-3180680b-ce07-4153-ae7d-63234a52238b.png)

### Total 5-Star Reviews:

- Vine: ![image](https://user-images.githubusercontent.com/102273449/185757887-b3abcca1-8f7a-4d19-ac50-09980d8f8b0c.png)
  
- Non-Vine: ![image](https://user-images.githubusercontent.com/102273449/185757909-59547ce2-08d0-4b81-85df-300e6bf86a82.png)

### 5-Star Review Percentage:

- Vine: ![image](https://user-images.githubusercontent.com/102273449/185757931-f4d9e696-0ea4-476c-8466-df5f969aa19d.png)
  
- Non-Vine: ![image](https://user-images.githubusercontent.com/102273449/185757943-d055e89d-9efd-4a6f-8304-492151d536f9.png)



|   |Vine |Non-Vine |
|---|-----|---------|
|Total reviews| 59| 13,480|
|Total 5-Star Reviews|34|7,678|
|5-Star Review Percentage|57.62%| 56.95%|

## Summary

The percentage of 5-star reviews is slightly higher (0.67% higher) for Vine reviews than for non-Vine reviews. It is hard to tell if there is any positivity bias in the Vine program since the difference in percentage is small. Running a two-sample t test would be useful to determine if that difference is significant or not.
