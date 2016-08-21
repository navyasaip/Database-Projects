
1. NavyaBaseLite.java is the main file implementing the given specifications.
2. Information_schema is the default schema as given in the requirement.
3. Compile and Run the NavyaBaseLite.java file
4. Prompt (navyaSql) will be displayed.
5. Enter the commands.

NOTE: 	All commands should end with a semicolon(;)
	The Whole Command should be given in a single line.(No Multiple Line Commands.)

Commands:

1.SHOW SCHEMAS 		Displays all schemas defined in the database.
2.USE			Chooses a schema.(Default: information_schema)
3.SHOW TABLES 		Displays all tables in the currently chosen schema.
4.CREATE SCHEMA 	Creates a new schema to hold tables.
5.CREATE TABLE 		Creates a new table schema, i.e. a new empty table.
6.INSERT INTO TABLE	Inserts a row/record into a table.
			Note:   The values should be entered without any space.
			like: INSERT INTO Students VALUES(1,'Jason Day','1995-08-21',32);
			Not: INSERT INTO Students VALUES( 1, 'Jason Day', '1995-08-21', 32);
			This is because the values are split on comma(,) and the Number Values do not accept spaces( ).
7."SELECT-FROM" 	style Query (Displays all rows of a table)
8.“SELECT-FROM-WHERE” 	style query (Displays Selected rows of the table depending on the WHERE Clause)
			Valid Operators in WHERE Clause: "=", ">", "<"
9. EXIT 		Cleanly exits the program and saves all table and index information in non-volatile files. 