## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase) :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/Hbase_shell_command.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________



## HBase Overview

### What is HBase ?

Apache HBase is a column-oriented, NoSQL database built on top of Hadoop (HDFS, to be exact).
It is an open source, non-relational, distributed database modeled after Google's Bigtable and is written in Java.
It is developed as part of Apache Software Foundation's Apache Hadoop project and runs on top of 
HDFS (Hadoop Distributed File System), providing Bigtable-like capabilities for Hadoop. That is, it provides a 
fault-tolerant way of storing large quantities of sparse data (small amounts of information caught within a large 
collection of empty or unimportant data, such as finding the 50 largest items in a group of 2 billion records, or 
finding the non-zero items representing less than 0.1% of a huge collection).



### HADOOP RANDOM ACCESS DATABASES


DBMS like HBAE , MongoDB , couchDB and  Dynamo are the some of the databases which are used by the Hadoop Framework 
 to access the amount of the data.


### Feature of HBase
 
**Scalability:** HBase supports scalability in both linear and modular form

**Distributed storage:** HBase supports distributed storage like HDFS

**Consistency:** It supports consistent read and write operations

**API support:** HBase supports Java APIs so clients can access it easily

**MapReduce support:** HBase supports MapReduce for parallel processing of large volume of data

**Back up support:** HBase supports back up of Hadoop MapReduce jobs in HBase tables

**Real time processing:** It supports block cache and Bloom filters. So, real time query processing is easy

### Storage Mechanisms of HBase

HBase stores the data in column oriented manner. So each row in the HBase is has a primary key column. 
Row is the collection of Column families and column family is the collection of the columns. Each data 
stored in the column  have key value pair.

In Short view of defination of HBase , we can say

* Table is a collection of rows.
* Row is a collection of column families.
* Column family is a collection of columns.
* Column is a collection of key value pairs.


![hbase](https://github.com/maniram-yadav/HBase/blob/master/images/HBase-column-families.png)



### Difference between RDBMS and DBMS

![difference between dbms rdbms](https://github.com/maniram-yadav/HBase/blob/master/images/hbaserdbms.png)


### Application of HBase


* HBase is used whenever we need to provide fast random access to available data.

* It is used whenever there is a need to write heavy applications.

* Companies such as Facebook, Twitter, Yahoo, and Adobe use HBase internally. [Read More ](https://github.com/maniram-yadav/HBase/blob/master/Hbase_shell_command.md)



## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase)  :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/Hbase_shell_command.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________
