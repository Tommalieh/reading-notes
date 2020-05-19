# Advanced Mongo/Mongoose

### Why would a developer choose to make data models?!

 * A data model not only improves the conceptual quality of an application, it also lets you leverage database features that improve data quality. Developers can weave constraints into the fabric of a model and the resulting database. For example, every table should normally have a primary key. The database can enforce other unique combinations of fields. Referential integrity can ensure that foreign keys are bona fide and not dangling.

###  What purpose do CRUD operations serve?

 * To make the models able to provide four basic types of functionality. The model must be able to Create, Read, Update, and Delete resources.

### What kind of database is Postgres? What kind of database is MongoDB?

 * MongoDB is a cross-platform document-oriented database program. Classified as a NoSQL database program , an open source, non- relational database management system.

 * PostgreSQL is a relational database management system, general-purpose and object-relational database management system, 

### What's Mongoose and why do we need it?!
 
 * Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.

### Describe how NoSQL Databases scale horizontally

 * NoSQL databases are designed to expand horizontally and in Horizontal scaling means that you scale by adding more machines into your pool of resources.

### Give one strong argument for and against NoSQL Databases
 
 * NoSQL databases are highly and easily scalable, maintaining NoSQL Servers is Less Expensive, less server cost and also open-source. No Schema or fixed data model and support integrated caching.

 * NoSQL database is Open Source and Open Source at its greatest strength but at the same time its greatest weakness because there are not many defined standards for NoSQL databases,so no two NoSQL databases are equal. No Stored Procedures in mongodb (NoSql database). GUI mode tools to access the database is not flexibly available in market and it's too difficult for finding nosql experts because it is latest technology and NoSQL developers are in learning phase.


### Define three related pieces of data in a possible application for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.

 * Constraints are the rules that force DBMSs to check that data satisfies the semantics. ... constraints. There are several kinds of integrity constraints, described below. ... Neither the PK nor any part of it can contain null values. This is ... It means the reference from a row in one table to another table must be valid.

 * A department store is a large store, divided into departments which sell such products as furnishings, electronics, clothing, footwear, toys, cosmetics, and sometimes also groceries. ... A department store has several departments housed under the same roof to facilitate buying, customer service, and merchandising.

### Name 3 cloud based NoSQL Databases 

 1. Amazon DynamoDB

 2. Garantia Data

 3. IBM Cloudant


## Vocabulary Terms


| Term  | Defenition  |
|---|---|
| Database  | an organized collection of structured information, or data, typically stored electronically in a computer system. |
| Data Model  | data model documents and organizes data, how it is stored and accessed, and the relationships among different types of data. |
| CRUD | FCRUD is an acronym that comes from the world of computer programming and refers to the four functions that are considered necessary to implement a persistent storage application: create, read, update and delete. |
| Schema | schema is the skeleton structure that represents the logical view of the entire database. It defines how the data is organized and how the relations among them are associated. |
| Sanitize  | checking user input before storing it in a database or using it for any other purpose to prevent malicious code injection. |
| SQL  | domain-specific language used in programming and designed for managing data held in a relational database management system |
| NoSQL  | a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases. |
| MongoDB  | Cross-platform document-oriented database program. Classified as a NoSQL database program |
| Mongoose | Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB. |
| Record | a record is a group of related data held within the same structure. More specifically, a record is a grouping of fields within a table that reference one particular object. The term record is frequently used synonymously with row. |
| Document  | A document database is a type of nonrelational database that is designed to store and query data as JSON-like documents. Document databases make it easier for developers to store and query data in a database by using the same document-model format they use in their application code. |
| Object Relation Mapping (ORM)  | Object-relational mapping in computer science is a programming technique for converting data between incompatible type systems using object-oriented programming languages. This creates, in effect, a "virtual object database" that can be used from within the programming language. |
|   |   |

