
1) Extract the file and find the DavisBase jar file in gxr170001_CS6360_Project2\out\artifacts\DavisBase_jar

2) Open cmd prompt

3) Change directory path in the command line to the folder that has the jar file
   Eg- cd C:\Project _new2\attempt gxr 4\gxr170001_CS6360_Project2\out\artifacts\DavisBase_jar

4) Run the jar file using java -jar DavisBase.jar

5) Start entering the commands in the console. (Every command should be terminated by semicolon ;)

Commands Supported by DavisBase:

********************************************************************************
SUPPORTED COMMANDS

All commands below are case insensitive

	USE <database_name>;                                              Uses the database for subsequent queries. You have to select the database before querying any table.
	SHOW TABLES                                                       Displays a list of all tables in the current database.
	CREATE TABLE table_name[columname type constraint]                Creates a new table schema, i.e. a new empty table.
        DROP TABLE table_name;                                            Remove table data, its schema.and its metdadata
	INSERT INTO table_name VALUES value_list                          Inserts a single record into a table (value_list size must be n).
	UPDATE table_name SET column_name = value,...  [WHERE condition]  Modifies one or more records in a table.
	SELECT * FROM table_name;                                         Display all records in the table.
	SELECT * FROM table_name WHERE rowid = <value>;                   Display records whose rowid is <value>.
	SELECT [column_list] FROM table_name WHERE rowid = <value>;       Display the specified column values for records whose rowid is <value>.
	SELECT [column_list] FROM table_name WHERE columnname = <value>;  Display the specified column values for records whose attribute/field named columnname has the value <value>.
        HELP;                                                             Show this help information
	EXIT;                                                             Exit the program

	DELETE FROM table_name [WHERE condition]                          Deletes one or more records from the table.


********************************************************************************

Note:
----
The table files (.tbl files) and database directories are stored in the root directory of the project. The metadata directory and the
tables are created as per the requirement.In case of error in the catalog file, delete the contents in the data directory and rerun the project.
