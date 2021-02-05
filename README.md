# Amazon_Vine_Analysis

##### Overview of Analysis

This challenge analyzes determines if the Amazon Vine program has a bias toward favorable reviews from Vine members. We use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics. I took a look at the reviews for video games.

##### Results
<p align="center"> Number of Reviews </p>
* Non-vine Reviews

<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Amazon_Vine_Analysis/blob/main/images/Non-vine%20reviews.PNG">
</p>

* Vine Reviews

<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Amazon_Vine_Analysis/blob/main/images/Vine%20Reviews.PNG">
</p>

<p align="center"> Number of 5 Start Reviews </p>
* Non-Vine 5 Star Reviews

<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Amazon_Vine_Analysis/blob/main/images/5starrev-nonvine.PNG">
</p>
                                     
* Vine 5 Star Reviews

<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Amazon_Vine_Analysis/blob/main/images/5starrev-vine.PNG">
</p>
 
 <p align="center"> Percentage of 5 Start Reviews </p>

* Percentage of Non-Vine 5 Star Reviews

<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Amazon_Vine_Analysis/blob/main/images/percentrev-nonvine.PNG">
</p>
                                     
* Percentage of Vine 5 Star Reviews

<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Amazon_Vine_Analysis/blob/main/images/percentrev-vine.PNG">
</p>

##### Summary

After the analysis we discovered 51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine 5 star reviews were only 39%. This shows a positivity bias for reviews in the Vine program.

An additional analysis would be to analyze the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
