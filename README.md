# Amazon_Vine_Analysis

## Overview
The purpose of the project is to analyze Amazon reviews written by members of the paid Amazon Vine program. In order to complete this analysis, I used a subset of data that pertained to the video game subcategory of Amazon. I then performed an ETL on this data by using AWS, Google Colaboratory, PostgreSQL, and PySpark. After that, I took a closer look at one of the tables I made during the ETL phase regarding the vine reviews to determine if there was any positivity bias for reviews in the Vine Program.

# Results
1) How many vine reviews and non-Vine review was there?
    There were 94 vine reviews and 40,471 non-vine reviews.
2) How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    There were 48 5-star vine reviews adn 15663 5-star non-vine reviews.

3) What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews    were 5 stars?
    51.06% of the vine reviews were 5-stars while 38.7% of the non-Vine reviews were 5-stars

# Summary
After looking that the results, I  conclude that there is a positivity bias for reviews in the Vine program. It is important to note that while the non-vine sample size was very large, the vine sample size was less than 100 entries. While 94 entires is still a decent number to sample with, it could lead a less signifcant result. In addition to the current analysis, I could take it a step further and see the percentage of those who purchased the product by filtering through the verified_purchase column to either confirm or fail to confirm if there is a positivity bias for reviews in the Vine program.

