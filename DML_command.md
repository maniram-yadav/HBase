## [:arrow_left:Previous]() :point_left:____________________________ :point_right:        [Next :arrow_right:]()

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________


### DML Command
  **DML** stands for Data Manipulation Language. These commands are used for storing , retreiving , updating and other operation related to data manipulation which has been stored in the table.
 > ___________________________________________________________________________________________

##### put
 **put** command is used for storing the data in the table.
 
 Query Format :point_down:
 
 ```
 put ’<table name>’,’<row id>’,’<column family>:<column name>’,’<value>’
 ```
  
 **Example :point_down:**
 ![put command](https://github.com/maniram-yadav/HBase/blob/master/images/put.png)
 
> ___________________________________________________________________________________________

##### get

**get** command is used for retreive data from the table.

 Query Format :point_down:
 
 ```
 get ’<table name>’,’<row id>’
 ```
  
 **Example :point_down:**
 ![put command](https://github.com/maniram-yadav/HBase/blob/master/images/row1.png)
 .
 In above example we have retreived all the data from  that row which have id **row1**.
 **_programmer_** and **_manager_** are the family of the table. **_name_** and **_age_** are the column of each 
 column family.
 
 We can also fetch data from a particular column family of the row by using below given query format.
 
 ```
 get ’<table name>’,’<row id>’,'<column family name>'
 ```
  
 **Example 1 :point_down:**
 ![put command](https://github.com/maniram-yadav/HBase/blob/master/images/getprogrammer.png)
 
 In above example we have fetched data of the row which have id **row1** and column family name is **manager**.


 **Example 2 :point_down:**
 ![put command](https://github.com/maniram-yadav/HBase/blob/master/images/getprogrammer.png)
 
In above example we have fetched data of the row which have id **row1** and column family name is **programmer**.


> ___________________________________________________________________________________________


###### data updation
Ther is not any update command in the HBase. For updating the value we overwrite the data by using **_put_** command. 
which has been mentioned above in this tutorial.

Query Format :point_down:

```
 put '<table name>','<existing row id>','<existing column family>:<existing column name>','<new value>'
```

**Example :point_down:**

 ![put command](https://github.com/maniram-yadav/HBase/blob/master/images/update.png)


> ___________________________________________________________________________________________

##### data deletion

**delete command**

Query Format :point_down:

```
 delete '<table name>','<existing row id>','<existing column family>:<existing column name>'
```

**Example :point_down:**

 ![delete command](https://github.com/maniram-yadav/HBase/blob/master/images/delete.png)


**deleteall command**
*deleteall* command is used for delteing all the values from a particular row. In this method we use the row id of the row for deletion.

Query Format :point_down:

```
 deleteall '<table name>','<existing row id>'
 ```

**Example :point_down:**

 ![deleteall command](https://github.com/maniram-yadav/HBase/blob/master/images/deleteall.png)



## [:arrow_left:Previous]() :point_left:____________________________ :point_right:        [Next :arrow_right:]()

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________
