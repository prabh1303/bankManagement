# **Banking Complaint and Loan Management System**
## Project Description 
Database will include details of customers such as Customer Id(Primary Key), Name, Email-ID, DOB, Home Branch, City, State, Balance, Account Number. These all are attributes of Customer Entity Set.<br>
Other Entity Set will be of Complaint which will have the following attributes:<br>
Customer ID (Foreign Key)<br>
Current Status<br>
Type of complaint<br>
No of days<br>
Primary key is combination of customer ID and type.<br>
Complaint and Customer Table will have complaint lodge relation between them.
The next Entity set is of Loan Details which have Loan No, Loan Date, Amount, Customer ID(Foreign Key) as attributes.
Customer and Loan Table will be having borrow relation between them.<br>
No of days since the complaint has been lodged is considered as an attribute of relation between Complaint and Customer.<br>
If the complaint is not resolved in 15 days, then it will be redirected to higher authority, Manager in our case. Manager have Name, Manager ID(Primary Key), Phone Number, Customer ID(Foreign Key) as attributes.

