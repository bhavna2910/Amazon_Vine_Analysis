# Amazon_Vine_Analysis
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

# Rasults:
### **Vine Reviews**
* Total Paid Reviews - 94

### **Non-Vine Reviews**
* Total Unpaid Reviews - 40471

### **Total Number of 5-Star Reviews
* **Vine Reviews** - 48
* **Non-Vine Reviews** - 15663

### Percentage of 5-star reviews
* **Vine Reviews** - 51.06
* **Non-Vine Reviews** - 38.70
