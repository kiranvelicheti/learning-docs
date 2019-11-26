# Hibernate Info
Hibernate is and JPA implementation using ORM model.
It resides on JDBC and is data base egnostic as queries are implemented in HQL which can be run against any data base.

# ACID
  Atomicity – each transaction either succeeds completely or is fully rolled back.
  Consistency – data written to a database must be valid according to all defined rules.
  Isolation – When transactions are run concurrently, they do not contend with each other, and act as if they were being run sequentially.
  Durability – Once a transaction has been committed to the database, it is considered permanent, even in the event of a system failure.

# When to choose SQL:
If your data is very structured and ACID compliance is a must, SQL is a great choice.
If data needs to be querried more frequently.

# When to choose NOSQL:
When large amounts of unstructred data needs to be stored 
When you do not limit the  number of data types to be stored 
To speed up the development
Make use of horizontal scalling and cloud storage
