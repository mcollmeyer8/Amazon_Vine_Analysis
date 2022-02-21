# Amazon_Vine_Analysis

## Overview
My team was tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. We were given approximately 50 datasets, and told to choose 1 from the group for our project. My team chose a Beauty dataset. Using PySpark, we were able to extract the data from the dataset, and create several DataFrames full of information about customer reviews. We uploaded the collected data into pgAdmin tables. We also created a second Google Colab Notebook, to dive deeper into the data and determine if there is any bias towards reviews that were written as part of the Vine program.

## Results
### - How many Vine reviews and non-Vine reviews were there?
There were a total of 5,115,666 reviews - 33,309 Vine reviews and 5,082,143 non-Vine reviews.

### - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were a total of 3,254,753 5-star reviews. Of that total, 12,429 were Vine reviews and 3,242,324 were non-Vine reviews.

### - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
0.38% of Vine reviews were 5 stars, whereas 99.62% of non-Vine reviews were 5 stars.

## Summary: 
Per our results, there is not a positivity bias for reviews in the Vine program. In fact, our results seem to prove the opposite. The Vine participants were much lower with their scores than non-Vine participants. It would be interesting to look closer at the Vine participants data, to determine average star-rating, or to see if there was a particular star-rating that occurred more frequently. 
