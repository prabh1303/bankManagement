Database will include details of customers such as Customer Id (Primary Key), Name, Account Number, Date of Birth, Email-ID, Address, Home Branch and Balance. These all are attributes of Customer Entity Set. 
Other Entity Set will be of Complaint which will have the following attributes:
Customer ID (Foreign Key)
Current Status
Type of complaint (Discriminator)
No of days
Complaint and Customer Table will have complaint lodge relation between them.
The next Entity set is of Loan Details which have Loan No (Discriminator), Loan Date, Amount, Customer ID(Foreign Key) as attributes.
Customer and Loan Table will be having borrow relation between them.
No of days since the complaint has been lodged is considered as an attribute of relation between Complaint and Customer.
If the complaint is not resolved in 15 days, then it will be redirected to higher authority, Manager in our case. Manager have Name, Manager ID (Primary Key) Phone Number, Customer ID(Foreign Key) as attributes.

