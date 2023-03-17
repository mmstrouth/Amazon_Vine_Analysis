# Amazon_Vine_Analysis

## Overview of Analysis
The objective of this project was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Results

* There were a total of 170 reviews by reviewers in the Vine Program
* There were a total of 37840 reviews by reviewers not in the Vine Program
* 65 of 170 Vine 5-Star reviews were 5-Stars
* 20612 of 37840 Non-Vine 5-Star reviews were 5-Stars
* 38% of Vine 5-Star reviews were 5-Stars
* 54% of Non-Vine 5-Star reviews were 5-Stars

Percentage of Vine reviews that were 5 stars  
![This is an image](https://github.com/mmstrouth/Amazon_Vine_Analysis/blob/df41fd56be71c5a642086fb2fa38eb3a9c873cb4/paid_proportion.png)

Percentage of non-Vine reviews that were 5 stars  
![This is an image](https://github.com/mmstrouth/Amazon_Vine_Analysis/blob/c81b485bfb9d1cac7389b65c2267852666b67397/unpaid_proportion.png)


## Summary
Overall, it does not appear as though those participating in the Vine program are more likely to give 5-star reviews compared to those not participating (38% vs. 54%). In fact, they may less likely, solely because they are being paid or possibly because the quality of the product is truly worse.
In terms of additional analysis, I would perform a two-sample z-test to determine if there is a statistically significant difference between the proportion of Paid reviews who gave 5-stars and Unpaid reviews who gave 5-stars. 
