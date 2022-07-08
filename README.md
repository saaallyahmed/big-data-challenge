# big-data- "Alexa, can you handle big data?"


We Used Google Colab Notebook as a `ipynb` file and  This will be the main script to run for analysis. We also  add any SQL queries you used to a `.sql` file.



## Project

We put our ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. Our first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal Was using PySpark or SQL to perform a statistical analysis of selected data.


## project scope


* We used the furnished schema to create tables in our RDS database.

* We created two separate Google Colab notebooks and **extract** two datasets from this list at [review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), one into each notebook.

  **Note:** we used two separated colab notbooks because It is possible to ETL both data sources in a single notebook, but due to the large data sizes, it will be easier to work with these S3 data sources in two separate Colab notebooks.

* We made it  to handle the header correctly. So we can read the file without the header parameter, we found that the column headers are included in the table rows.

* We used SQL, first and used Spark on Colab to extract and transform the data and load it into a SQL table on our RDS account. Perform our analysis with SQL queries on RDS.

* While there are no hard requirements for the analysis, consider steps we could take to reduce noisy data, e.g., filtering for reviews that met a certain number of helpful votes and total votes.



## References

Amazon customer Reviews Dataset. (n.d.). Retrieved April 08, 2021, from: [https://s3.amazonaws.com/amazon-reviews-pds/readme.html](https://s3.amazonaws.com/amazon-reviews-pds/readme.html)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
