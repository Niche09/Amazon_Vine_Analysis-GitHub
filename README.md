# Amazon_Vine_Analysis-GitHub

Summary
-------------

This project is analyzing Amazon reviews written by members of the Amazon Vine program and is attempting to determine if there are any 
descrepencies between Vine members and non-Vine memebers reviews.

In order to determine any biasis towards good reviews from Vine members vs non-Vine members, we have to find the percentage of 5 star ratings vs total ratings. 
 I attempted to extract the data, transform it and then connect to AWS RDS instance and then load the transformed data into PgAdmin. 
 Using PySpark I tried to use imported PySpark libraries to connect to Postgres in order to create SQL tables. 
