# Amazon_Vine_Analysis

## Overview
We are analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. We picked a dataset and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We then used PySpark, Pandas, and SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.  Below we are providing a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

### Results
-   Total Number of Reviews that Paid (4,751,577)
-   Total Number of Reviews that were unpaid (105979)
-   Total Number of 5-Star Reviews that Paid (0)
-   Total Number of 5-Star Reviews that were unpaid (67580)
-   Total % of 5-Star Reviews that were unpaid (63.77%)
-   Total % of 5-Star Reviews that paid (0.00%)
#### Summary
There is a positivity bias of 5-Star Reviews that were unpaid. 5-Star reviews were hard to come by when they paid.