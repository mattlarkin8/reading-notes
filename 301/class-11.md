# **Mongo and Mongoose**

## **nosql vs sql**

### Differences between SQL and NoSQL databases

- SQL databases are Relational Databases and NoSQL Databases are non-relational or distributed.
- SQL databases are table based and NoSQL is document based.
- SQL has predefined schema and NoSQL has dynamic schema.
- SQL is vertically scalable while NoSQL is horizontally scalable.
- SQL databases use Structured Query Language to define and manipulate data. NoSQL databases have queries that are focused on the collection of documents.

### What kind of data is a good fit for an SQL database?

SQL databases are good for heavy duty transactional applications.

### Give a real world example.

MySQL can be used to serve this purpose, especially with its server sharding ability.

### What kind of data is a good fit a NoSQL database?

NoSQL is best used for hierarchical data storage. It is preferred for large data sets.

### Give a real world example.

Hbase is used for this purpose.

### Which type of database is best for hierarchical data storage?

NoSQL is better because it stores data using key-value pairs.

### Which type of database is best for scalability?

NoSQL databases are better because they can scale both horizontally and vertically. You can upgrade the hardware of the server to handle increased load instead and add additional servers when needed.

## **sql vs nosql**

### What does SQL stand for?

SQL stands for Structured Query Language.

### What is a relational database?

A relational database stores data across multiple tables that are connected based on their relationship.

### What type of structure does a relational database work with?

Relational databases work with tables.

### What is a ‘schema’?

A schema is basically a rule for formatting data storage. Everything needs to follow this set of rules, which may require you to adapt your data to follow this format before being able to store it.

### What is a NoSQL database?

NoSQL is a database that uses documents to store data rather than tables. It does not have any schema, which makes it a very flexible data storage solution.

### How does it work?

NoSQL has collections. These collections hold many documents. They can hold any data you want and the format can very between each document because there isn't any schema in NoSQL.

### What is inside of a Mongo database?

A Mongo database holds many collections that can each have many documents. Inside the documents, you find the data being stored as key-value pairs. This data and its format can very greatly between each document due to the flexible nature of NoSQL.

### Which is more flexible - SQL or MongoDB? Why?

Mongo is more flexible because it doesn't use schemas. This lets the user store whatever data they want, however they want.

### What is the disadvantage of a NoSQL database?

Not having relations can be an issue if you need to write to the database a lot. Since NoSQL can have the same data stored in multiple documents and collections, multiple write requests will have to be made for a single change because each document must get updated separately. NoSQL also struggles with complex requests and heavy duty transactional data.

## **Things I want to know more about**

I want to learn a bit more about SQL storage. I think the concept of how a relational database works is really cool and tieing the tables together appeals to my logical thinking.
