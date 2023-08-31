# Analysing-a-bank-term-deposit-sub-using-Power-BI

# Task 1
This is the first time I will be using Microsoft Power BI to analyze data and visualize all thanks to Chinonso Promise who took her time to explain the process and made it easy for me.

Below I will be using a bank term deposit subscription dataset to visualize and gain insights.

The task for this analysis is;

* Import the ‘Bank Term Deposit Subscription’ dataset into your Power BI Desktop using the CSV file option
* Load the dataset into a database in SQL Server, connect your Power BI desktop to this database, and import only the first 25 rows into your desktop for analysis

First I will load the Microsoft Power BI desktop app on my laptop and import the dataset using the "get data" and choose CSV File on Power BI

Question 1:Import the ‘Bank Term Deposit Subscription’ dataset into your Power BI Desktop using the CSV file option

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/aa0f71ef-b60b-452c-8b29-beb6fe8d2059)

Question 2: Load the dataset into a database in SQL Server, connect your Power BI desktop to this database, and import only the first 25 rows into your desktop for analysis

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/da96f9e9-302e-46f2-8894-9c4ddc816a29)


# Task 2

Task 2 involves loading the Employee, Salary, and Department Dataset into Power BI and extensively cleaning out the dirty dataset at the end I am to merge all three datasets and load them on Power BI.
Below is how I achieved a clean data set using Power BI

First I load my Dataset into Power BI and transform it so I am taken to the Power query interface. this is the interface I am going to be using to clean out my dirty dataset before taking it to the Power BI interface proper for analysis and visualization.

After loading the dataset into the power query interface, I checked the table headers for mistakes and corrected them accordingly.
I changed the datatypes to text for most of them as I don't want mix-ups when performing analysis with the aggregate function.
At the end of the cleaning process, I arrived at a clean dataset below

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/9bc20148-dffa-4fca-a073-83935624d2d3)

Above is my cleaned-out Employee dataset!!!

I cleaned out the Salary Dataset and removed null values and blank spaces. Below is the clean dataset

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/3a6da76f-cbff-4f35-8451-ff97bf634e63)

I also performed a similar task on the Department dataset. Below is my clean Dataset.

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/b27da4e2-58d5-47de-9a7b-4e3e486f71fc)

After cleaning, I first merged the employee table and the Salary table together

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/fe3bac04-748a-4dc9-953f-b20cb3e36d48)

Then I Merged the new table to the Department table.

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/1542a410-dfbe-47d7-af54-4900fbc41194)


Then I loaded the merged dataset into Power BI

![image](https://github.com/Omablu/Analysing-a-bank-term-deposit-sub-using-Power-BI/assets/119351114/4b7c0c0c-54d6-43ff-a8e2-ca0bb74522cb)


Above is a cleaned and merged table ready for Visualization!!!






