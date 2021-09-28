# ONLINE BANKING ANALYSIS
In this project we are working on a loan dataset, customer credit card dataset and a bank transaction dataset by using Apache Spark, which is a data processing framework that can quickly perform processing tasks on very large data sets, and can also distribute data processing tasks across multiple computers, either on its own or in tandem with other distributed computing tools. Using these datasets and Spark SQL we have created various use cases pertaining to real life scenarios in banking.

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/553931998293758/1733511036908678/113857780564717/latest.html

# TOOLS AND TECHNOLOGIES

* SPARK
* HDFS
* HIVE
* DATAFRAMES
* PYSPARK
* SPARK SQL
* JUPYTER NOTEBOOK
* DATABRICKS

# FEATURES
List of usecases performed on each datasets
### USE CASES FOR LOAN DATASET

* The number of loans on each category
* The number of loans taken on each occupation
* Know the number of members who taken more than 1lack loan
* Number of members whose overdue is more than 5
* The number of members whose debt record is less than 20k
* Marital status of loans takers
* Number of loans in each category
* Partitioning dataframe on column ‘Loan Category’
* Number of people with 2 or more returned cheques and income less than 50000

### USE CASES FOR CUSTOMER CREDIT DATASET

* The number of members who are eligible for credit card
* The number of members who are  eligible and active on bank
* The number of targeted persons for credit card
* The targeted persons count whose tenure is less than 5
* The targeted persons count who exited
* The number of targeted persons whose number of product is equal to 1
* Credit card users in Spain
* Number of customers who’s Estimated Salary less than 1 lakh and number of products more than 1.

### USE CASES FOR CUSTOMER TRANSACTION DATASET

* Count of transaction on every account.
* Maximum withdrawal amount of an account
* Minimum withdrawal amount of an account
* Maximum deposit amount of an account
* Minimum deposit amount of an account
* Sum of balance in every bank account
* Count of transaction methods what customers used for transaction.
* Number of transaction on each date.
* List of customers with withdrawal amount more than 1 lakh

# TABLE CONFIGURATION

![image](https://user-images.githubusercontent.com/63140467/133890621-cfe026ce-a6a0-458f-a03a-77ae7304314f.png)

# GETTING STARTED
GitHub clone URL: https://github.com/rajib1007/PROJECT1.git

Download VMware Workstation: https://drive.google.com/file/d/1v0dzEJK-cDD7nL7cX5mbJ4evl3s3u-Ib/view?usp=sharing

##### Download UBUNTU iso file and create an image on VMware
https://ubuntu.com/download/desktop
##### Follow this link to install JUPYTER NOTEBOOK on UBUNTU
https://www.digitalocean.com/community/tutorials/how-to-set-up-jupyter-notebook-with-python-3-on-ubuntu-20-04-and-connect-via-ssh-tunneling

##### Install required tools ans set path

sudo apt-get install openjdk-8-jdk

wget https://dlcdn.apache.org/spark/spark-3.1.2/spark-3.1.2-bin-hadoop3.2.tgz

tar xvzf spark-3.1.2-bin-hadoop3.2.tgz

wget https://archive.apache.org/dist/kafka/2.0.0/kafka_2.11-2.0.0.tgz

tar xvzf kafka_2.11-2.0.0.tgz

##### Install kafka on jupyter-
pip install kafka-python

##### Run usecases

# CONTRIBUTERS

* SIDHANT SEHGAL
* ABHILASH REDDY
* AKHIL
* ANAND KUMAR
* VENKATESH VENKAT
