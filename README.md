# Amazon-Vine-Analysis

## Overview of Analysis

This analysis will focus on analyzing Amazon reviews written by members of the paid Amazon Vine program. The reviews are specifically for the Amazon Reviews for Health and Personal Care items. 

## Results

The data preparation utilizes PySpark, pgAdmin, Pandas, SQL, AWS, and the ETL process to analyze and create summaries. The summaries are generated on the <a href="Amazon_Reviews_ETL.ipynb">Amazon Reviews ETL file</a> and <a href="Vine_Review_Analysis.ipynb">Vine Review Analysis file</a>. 

### Total Number of Vine and Non-Vine Reviews

There are 497 Vine reviews and 120863 non-Vine reviews.

### Total Number of 5 Star Vine and Non-Vine Reviews

There are 220 Vine reviews and 74470 non-Vine reviews that were 5 stars.

### percentage of 5 Star Vine and NNon-Vine Reviews.

44% of the Vine reviews and 62% of the non-Vine reviews were 5 stars.

## Summary

The percentage of Vine reviews with 5 stars is 44%, whereas the percentage of non-Vine reviews is 62%. This showcases that there is no positivity bias for reviews in the Vine program.

An additional analysis we could conduct is a statistical distribution analysis to see the mean, median, mode and standard deviation.