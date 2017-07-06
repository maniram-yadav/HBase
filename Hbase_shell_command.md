
## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase/blob/master/HBase_Overview.md) :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/HBase_Create_Table.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________


### Useful HBase Shell Command

#### General Commands

> **whoami** : Provide information about the user and related group of Linux operation system


![whoami](https://github.com/maniram-yadav/HBase/blob/master/images/whoami.png)


> **version** : Used for getting the HBase version


![version](https://github.com/maniram-yadav/HBase/blob/master/images/version.png)



> **table_help** : To get information about table related command


![table help](https://github.com/maniram-yadav/HBase/blob/master/images/tablehelp.png)



> **status** : Provide status of HBAse like no. of server running.


![status](https://github.com/maniram-yadav/HBase/blob/master/images/status.png)


#### Data Definition Language Commands

These are commands which operate on the table.
> **create** - Creates a table.

> **disable** - Disables a table.

> **is_disabled** - Verifies whether a table is disabled.

> **list** - Lists all the tables in HBase.

> **is_enabled** - Verifies whether a table is enabled.

> **enable** - Enables a table.

> **alter** - Alters a table.

> **describe** - Provides the description of a table.

> **exists** - Verifies whether a table exists.

> **drop** - Drops a table from HBase.

> **drop_all** - Drops the tables matching the ‘regex’ given in the command.


#### Data Definition Language Commands

These are commands which operate on the table.

> **put** - Puts a cell value at a specified column in a specified row in a particular table.

> **deleteall** - Deletes all the cells in a given row.

> **delete** - Deletes a cell value in a table.

> **get** - Fetches the contents of row or a cell.

> **count** - Counts and returns the number of rows in a table.

> **scan** - Scans and returns the table data.

> **truncate** - Disables, drops, and recreates a specified table.

##### Starting HBase Shell
Make sure you are coming through the HBase Tutorial. You have follow all the instruction given there. If not follow this link...
[Starting HBase Server]()

Then follow the below given command.
```
hbase shell
```
![hbase shell](https://github.com/maniram-yadav/HBase/blob/master/images/hbaseshell.png)

So now hbase shell has been started. we can execute HBase shell command here on the terminal.
You can list all the tables by following the command given below ..
```
list
```
**Example:**:point_down:
![list database](https://github.com/maniram-yadav/HBase/blob/master/images/list.png)

All the table which exist has been listed. [Read More](https://github.com/maniram-yadav/HBase/blob/master/HBase_Create_Table.md)
> ___

## [:arrow_left:Previous](https://github.com/maniram-yadav/HBase/blob/master/HBase_Overview.md) :point_left:____________________________ :point_right:        [Next :arrow_right:](https://github.com/maniram-yadav/HBase/blob/master/HBase_Create_Table.md)

_____________________________ :door: [Home](https://github.com/maniram-yadav/HBase) :door: _____________________________
