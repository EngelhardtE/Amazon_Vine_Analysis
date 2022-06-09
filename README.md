# Amazon_Vine_Analysis

## Overview

The purpose of this project is to determine whether or not Amazon Vine members are more inclined to leave positive reviews on products (specifically watches) than non-Vine members. Using PySpark to perform the ETL process allows for the data to be analyzed within both Google Collaboratory and Jupyter Notebook. 

## Results

- Overall, there were 47 Vine member reviews and 8,362 non-Vine member reviews 
- Of the 47 Vine member reviews, 15 were 5 star reviews
- Of the 8,362 non-Vine member reviews, 4,332 were 5 star reviews
- Based on this data, 31.9% of Vine members gave 5 star reviews compared to 51.8% for non-Vine members 

![Vine_Stats](Resources/Vine_Stats.png) 

## Summary

Based on this data sample, there is not a positivity bias for Vine members when writing reviews. Statistically, non-Vine members were more likely to leave 5 star reviews, although the sample size of Vine members was much lower than non-Vine members. Due to this small sample size, it might prove worthwhile to explore potential biases within certain product types. For example, technology versus clothing. This could determine whether consumers are more critical of certain products depending on their type or function. 
