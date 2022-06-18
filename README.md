# Amazon_Vine_Analysis

## CHALLENGE OVERVIEW
---
This project goal is to analyzing Amazon reviews written by members of the paid Amazon Vine program.

## FEATURES AND DATA SOURCES
- Data Source: [amazon_reviews_us_Tools_v1_00.tsv.gz](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Tools_v1_00.tsv.gz)
- Programming Files: `challenge_squema.sql`, `Amazon_Review_ETL.ipynb`, `Vine_Review_Analysis.ipynb`,
-  Data Tools: `Pandas`, `PySpark`, `POstgresql`
-  Software: `Google Colab`, `Python`, `PgAdmin`, `AWS RDS`, `AWS s3`

## Challenge Deliverables
- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)


## Results
---

### Deliverable 1: Perform ETL on Amazon Product Reviews



![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%201%20-%20I.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%201%20-%20II.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%201%20-%20III.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%201%20-%20IV.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%201%20-%20V.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%201%20-%20VI.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%201%20-%20VII.png)

### Deliverable 2: Determine Bias of Vine Reviews

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%202%20-%20I.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%202%20-%20II.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%202%20-%20III.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%202%20-%20V.png)

![](https://github.com/Bruno-OGSilva/Amazon_Vine_Analysis/blob/0faa860ca8f2c5567f4a56a602fd0e1b0032d319/Assets/Delivable%202%20-%20VI.png)

#### Deliverable 3: A Written Report on the Analysis (README.md)

1. How many Vine reviews and non-Vine reviews were there?
- Total Vine reviews: 285
- Total non-Vine reviews: 31,542

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- 5-star Vine reviews: 163
- 5-star non-Vine reviews: 14,164

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- % of 5-star Vine reviews: 57.19%
- % of 5-star non-Vine reviews: 46.33%

The Analysis above indicates that there is evidence of positivity bias for Vine-member reviews.



