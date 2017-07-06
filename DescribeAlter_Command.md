## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase/blob/master/Exists_command.md) :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/disable_command.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________


#### describe
**_describe_** command is used to describe the table structure.

**Query Format :point_down:**

```
 describe '<table name>'
```

**Example :point_down:**
![describe](https://github.com/maniram-yadav/HBase/blob/master/images/describe.png)


### alter command
 alter command is the DDL(Data Definition Language) command which is used for modify , change the definition of the table.

**Adding new column family**

Query Format :point_down:

```
alter '<table name>',NAME=>'<column family name>'
```


**Example :point_down:**
![column family](https://github.com/maniram-yadav/HBase/blob/master/images/addcolumn.png)


**Number of cells per column family**
 
 You can add maximum number of cells per column family. By using below given query..
 Query format :point_down:
 
 ```
 alter '<table name>',NAME => '<column family name>' , VERSIONS => '<Number of cells>'
 ```
 
 **Example  :point_down:**
 
 ![number of cells](https://github.com/maniram-yadav/HBase/blob/master/images/numbercells.png)



**Deleting column family**
 
 Query format :point_down:
 
 ```
 alter '<table name>','delete' => '<column family name>'
 ```
 
 **Example  :point_down:**
 
 ![number of cells](https://github.com/maniram-yadav/HBase/blob/master/images/delete.png)


## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase/blob/master/Exists_command.md) :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/disable_command.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________
