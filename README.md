# OnlineShoppingWebSpring
This is a website which provides online Shopping service. It used spring framework and hibernate.   

Show the structure of the project:
![avatar](images/processgraph.png)

Database:
ORM is a programming technique that lets you manipulate data from a database using object-oriented programming language

We will use Hibernate as the ORM libraries.

Hibernate is an object-relational mapping tool for the java programming language which implements the Java Persistence API.
Hibernate's primary feature is mapping from Java classes to database tables and mapping from Java types to SQL data types.

There are three important inferfaces of Hibernate framework:
	1. SessionFactory: used for mapping a single database
	2. Session: the interface between java application code and hibernate framewordk and provides methods for CRUD operation
	3. TransactionL used to specify atomic units of work

ER Diagram
![avatar](images/ER.png)

We run mysql database on RDS from AWS.