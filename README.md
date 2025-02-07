# Learning MySQL by Creating a Sample Database based on Five Customers and Their Transactions

## Objective
  
The objective of this SQL Home Lab is to set up and manipulate a database using MySQL to store and analyze customer transaction data. By completing this lab, you'll gain hands-on experience with creating databases, importing data, performing SQL queries, and understanding relational databases. The main focus is on using SQL queries to aggregate, filter, and analyze transactional data for meaningful business insights.


### Skills Learned

- Database Setup: Create databases and tables, manage relationships (foreign keys).
- Data Insertion: Insert data manually and import CSV files.
- SQL Joins: Use INNER JOIN to link data across tables.
- Data Aggregation: Use COUNT(), SUM(), and other aggregate functions to analyze data.
- Filtering & Sorting: Apply WHERE, HAVING, and ORDER BY clauses for data analysis.

### Tools Used

- VirtualBox 
- Kali Linux VM
- MySQL

## Steps

*Ref 1-3: Installing and running MySQL on Kali Linux. Open a terminal and update the package list, then install MySQL. "sudo apt update && sudo apt upgrade -y", start and enable MySQL "sudo systemctl start mysql sudo systemctl enable mysql", and secure the install "sudo mysql-secure-installation*

![image](https://github.com/user-attachments/assets/0b522569-10ec-44ad-9351-f660aba5fa6b)

![image](https://github.com/user-attachments/assets/a740dfec-fa59-4109-a4d5-cf8b5aebc238)

![image](https://github.com/user-attachments/assets/100f4253-9f0e-4447-bb6b-d35950129f58)

*Ref 4: Now that we got MySQL up and running on Kali Linux, lets punch in some data points and explore the world my SQL*

![image](https://github.com/user-attachments/assets/1debfc9b-aa49-4831-b51a-dd5a09f52f24)

*Ref 5: A simple command of show databases; will give us a prompt as shown in the picture. For SQL commands must always end with a ";"*

![image](https://github.com/user-attachments/assets/dc526aea-887b-4344-8c69-787676dcbd7e)

*Ref 6-9: Create a retail transaction database. Once MySQL is installed, log in as root and create a new database named retail_db. Inside this database, create two tables. Customers - stores customer details like names, email, phone, and address. Transactions - records puchases, linking each transaction to a customer. The customer_id field connects both tables, ensuring relational integrity. "(" if its not ";" it means that the statement is not done yet so you keep going, it's not till after you're done with inputting a list of data use ");". And a simple show tables; statement at the end to show the tables you've done.*

![image](https://github.com/user-attachments/assets/5d9acdb8-bacd-45b3-a2db-2fd75cc6e650)

![image](https://github.com/user-attachments/assets/a273f49d-29b2-4bf8-a669-003b4267118b)

![image](https://github.com/user-attachments/assets/68971114-5393-44af-9ee8-ab85ad45c906)

![image](https://github.com/user-attachments/assets/81efd297-1ada-4603-abed-a46e0fc79485)

*Ref 10-11: Now lets tackle a bigger database while manually inputting our own data. To make the data base more realistic, we manually insert our data using the "INSERT INTO" statements. Then use SELECT * FROM customers; statement to show the database. The "*" means all in that statement.*

![image](https://github.com/user-attachments/assets/a1f7dabd-698f-400e-a691-5f85136fc582)

![image](https://github.com/user-attachments/assets/80ad0b07-8f18-42f7-b0d1-3bdfeddde8ca)

*Ref 12-14: Add a few more customer names, email, phone, addresses and tranactions, then use statement SELECT * FROM customers.*

![image](https://github.com/user-attachments/assets/76b35fb4-d970-4164-a3d9-1172cc93ac15)

![image](https://github.com/user-attachments/assets/395a0c12-753f-488f-9171-9cef224ef97e)

![image](https://github.com/user-attachments/assets/83b4bf69-c505-4ab5-a0b7-3fc03eb8db68)

*Ref 15-16: Running queries for analysis. Once the data is loaded, we use SQL queries to analyze the dataset. As previously done we used SELECT * FROM customers statement to retrieve all customer records, count how many transactions each customer made, and we can use SUM and HAVING as clauses to identify customers who spent over $300.*

![image](https://github.com/user-attachments/assets/0d277a5c-4a83-4dd3-948e-a2afbcf0ea12)

![image](https://github.com/user-attachments/assets/a7fb8259-e050-47b0-aee7-175f979e2f20)

