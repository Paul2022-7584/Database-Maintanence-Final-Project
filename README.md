# Database-Maintanence-HCO-Project-Instructions PART I

1.  ERD
For this phase, assume you are a member of a team of database and Graphical User Interface (GUI) developers/analysts. As a member of the database team, you are required to create an ER Diagram that will facilitate the development of Health Care Options’ company-wide database (see the Heath Care Options, Inc. document in the Resources section for details on the company). It should be created using Entity-Relationship (ER) Assistant and include entities, attributes, and relationships.
The scope of the database includes all entities referenced in the case study.  The goal of this phase of development is to support a scheduling system that will replace the current spreadsheet process, but your database should be designed to support all of the company’s current and future needs.   Note that your team will not actually create the scheduling system.  You are responsible only for designing the database that will be used by the system.  Subsequent phases will include table design and broaden the scope to support billing and cost report compilation.  Thus, plan and design your initial database carefully, as it will affect your future deliverables.
2.  CREATE TABLE Statements
Based on your ERD design, in step 1, write and execute the CREATE TABLE statements for each of the tables.  Be sure to create primary, foreign key, and NOT NULL constraints as appropriate.
To receive full credit for this assignment, all of your CREATE TABLE statements must be executed in Microsoft Structured Query Language (MS SQL) Server.  
In addition to creating the tables, you must add at least 3 rows of data to each one.  If there are any errors in your ERD, you will likely find them yourself at this point in the process and make any needed adjustments to your design.  Remember, order matters when you are creating tables and loading data.  
Finally, execute the following commands for each table and print out the results to show that you have successfully performed the CREATE TABLE step of this assignment and have populated the tables correctly.
exec  sp_help [table name]
select * from [table name]

What you will submit:
Submit your ERD file (created in ER Assistant) along with a Word document that contains the following:
	1. CREATE TABLE statements for all of the tables in your ERD.
	2. Screenshots of each table you created after running the exec sp_help and select statements described above.

Use INSERT statements
(INSERT [Table Name] select (put in data, data for 2nd field, data for 3rd field).  (3 insert statements for each table).  

