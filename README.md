## Python-Course-Project
🚕 NYC Taxi Trip Analysis — Python Project

A Python-based exploratory data analysis (EDA) of NYC Taxi & Limousine Commission (TLC) trip data.
 This project focuses on using core Python data analysis tools to examine data quality, fare patterns, trip characteristics, and customer behavior.


### 📌 Project Objectives
* Perform initial data exploration and cleaning


* Identify data types and detect anomalies


* Analyze fare structure, trip distances, and payment behavior


* Compare patterns across vendors


* Document findings to support further analysis or modeling



### 🧰 Technologies Used
* Python 3
* pandas, NumPy
* matplotlib
* Google Colab



### 📊 Key Insights from the Analysis
* Most variables are correctly stored as numeric types; only three require conversion from object types.


* The distribution of fare_amount is irregular, with a maximum value of $1000 — far above the typical range between the 25th and 75th percentiles.


* Both fare_amount and total_amount contain negative values, indicating data quality issues.


* Typical trip distances range between 1–3 miles, but rare long-distance trips reach 33 miles, likely airport rides.


* Extreme outliers in total_amount are significantly higher than the rest and are not always associated with long trips.


* Credit card payments dominate, representing more than twice the volume of cash payments.


* Card-paying customers tip nearly 3× more often than cash-paying customers.


* There is no significant difference in the average total amount between the two TPEP providers.


* A data quality issue exists in passenger_count, where 27 trips are recorded with 0 passengers.





