# HDFS-and-Hive

For this Big-data project, I took the web-series data from Kaggle website, and converted that data into CSV file. The dataset contains 9 columns and 12500 rows approximately. Then using Ambari I imported the CSV file data into HDFS. After that I created one database and table inside that database using Hive. Then I loaded the web-series data into the Hive table and finally did some analysis on that dataset with the help of Hive queries. And also stored the output of Hive queries back into HDFS.

# Objective

We need to find some insights on it. For Business growth and to improve marketing strategy. Finding theright target audience.

* Find out the total number of user in this datasets;
* Find out the number of Facebook user above age of 30
* Do male Facebook user tend to have more friend or female user?
* How many like do young people receive on Facebook opposed to older member?
* Find out the count of Facebook user for each birthday month
* Do young member use mobile phone or computer for Facebook browsing?
* Do young member use mobile phone or computer for Facebook browsing?
   
# Technologies Used

HDFS: For storing large web-series dataset and provides easier access to hive tables.

Hive: Hive is used to facilitates easy data summarization, ad-hoc queries, and the analysis of web-seires datasets stored in Hadoop compatible file systems.

# Features

* Created a table in hive using HiveQL create command and loaded the data into a Hive table.
* Did some analysis on that dataset with the help of Hive queries.
* Stored output of Hive queries into a file in HDFS.
* Applied Partitioning and Bucketing concepts in Hive.

# References
* https://www.tutorialspoint.com/hive/hive_create_table.htm
* https://www.geeksforgeeks.org/hive-load-data-into-table/
* https://sparkbyexamples.com/apache-hive/hive-partitioning-vs-bucketing-with-examples/
