# Amazon Vine Analysis
#### Module 17 Challenge

## Project Overview
#### Purpose
The purpose of this project was to analyze Amazon reviews written by members of the paid Amazon Vine program for BigMarket, a marketing company, to determine if bias exists in favorable reviews for members and non-members of the Amazon Vine program.  This analysis will incorporate PySpark to initiate the ETL process, connect to an Amazon Web Service (AWS) Relational Database System (RDS) instance, load the data into pgAdmin, and use Google Colab to analyze the data.

#### Resources
+ Data Sources: [Amazon Sports Games Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
+ Software: pgAdmin 4, Amazon Web Services, Google Colab, PostgreSQL 14.6

## Results
#### Total Reviews for paying and non-paying members
+ Paying members

![image](https://user-images.githubusercontent.com/113741694/231605150-8fc0c3ef-e640-4bac-9d70-6028eca957d1.png)

+ Non-paying members

![image](https://user-images.githubusercontent.com/113741694/231605233-b8e33df4-6110-447d-bc39-fb0f9dc85983.png)

#### 5-star Reviews for paying and non-paying members
+ Paying members

![image](https://user-images.githubusercontent.com/113741694/231605456-d05133f6-4077-472a-93b1-7ed1d2738d8c.png)

+ Non-paying members

![image](https://user-images.githubusercontent.com/113741694/231605507-3f609b1f-7e44-4d8f-a597-b4fe16c85939.png)

#### Percentage of 5-star reviews for paying and non-paying members

+ Paying members

![image](https://user-images.githubusercontent.com/113741694/231605679-e235adc1-5e60-4a83-b468-f7a27e72d3e7.png)

+ Non-paying members

![image](https://user-images.githubusercontent.com/113741694/231605814-ed7a0666-ffcf-4645-a230-1bedf6d36753.png)

## Summary
According to the results, there is a positivity bias for non-paying members of the Amazon Vine Program.  The percentage of 5-star reviews for non-paying members is 53.03% and the percentage of 5-star reviews for paying members is 41.62%.  More analysis needs to be done to see how the star ratings are distributed.  A histogram would be an effective way to see if the star ratings are more evenly distributed for paying members than they are for non-paying members, thus creating a higher 5-star percentage for non-paying members.


#### Grader's Note



