## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase/blob/master/DescribeAlter_Command.md) :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/enable_command.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________

### HBase disable command
In HBase before deleting any table we must have to disable to that table.
**_disable_** command is used to disable the table. 

**Query Format :point_down:**
 

```
   diisable '<table name>'
```
 
**_<table name>_** in the above query is the name of the table which we want to disable.

#### drop command

After disbaling we can drop table by using command :point_down:


```
 drop '<table name>'
```
 
Above :point_above: mention query will delete the table. You can verify that table has been deleted or not by using command.
 
```
 list
```
 
It will list all the tables which exists. The table which has been deleted will not be shown in the list.
 
 
#### drop_all command
 
**_drop_all_** command is used to delete multiple table by using regx expression.

**_Example_** :point_down:
 
```
 drop_all 'emp.*'
```
 
The above :point_up: given query will delete all the table in which first three character of table name is *emp*.
 
If following are the tables exists in HBase cluster
 
 * employee
 * employer
 * employeeprofile
 * manager
 
Then first three table which name starts from *emp* i.e. **employee**, **employer** and **employeeprofile** will be delated by above given *drop_all* command.
 
 
## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase/blob/master/DescribeAlter_Command.md) :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/enable_command.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________
