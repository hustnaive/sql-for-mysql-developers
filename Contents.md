# PART I Introduction 
## CHAPTER 1 Introduction to MySQL
### 1.1 Introduction
### 1.2 Database, Database Server, and Database Language
### 1.3 The Relational Model 
### 1.4 What Is SQL? 
### 1.5 The History of SQL 
### 1.6 From Monolithic via Client/Server to the Internet  
### 1.7 Standardization of SQL  
### 1.8 What Is Open Source Software?
### 1.9 The History of MySQL  
### 1.10 The Structure of This Book  
## CHAPTER 2 The Tennis Club Sample Database 
### 2.1 Introduction 
### 2.2 Description of the Tennis Club 
### 2.3 The Contents of the Tables
### 2.4 Integrity Constraints 
## CHAPTER 3 Installing the Software
### 3.1 Introduction  
### 3.2 Downloading MySQL 
### 3.3 Installation of MySQL
### 3.4 Installing a Query Tool 
### 3.5 Downloading SQL Statements from the Web Site 
### 3.6 Ready?  
## CHAPTER 4 SQL in a Nutshell  
### 4.1 Introduction 
### 4.2 Logging On to the MySQL Database Server 
### 4.3 Creating New SQL Users  
### 4.4 Creating Databases   
### 4.5 Selecting the Current Database  
### 4.6 Creating Tables 
### 4.7 Populating Tables with Data
### 4.8 Querying Tables 
### 4.9 Updating and Deleting Rows 
### 4.10 Optimizing Query Processing with Indexes 
### 4.11 Views
### 4.12 Users and Data Security
### 4.13 Deleting Database Objects 
### 4.14 System Variables
### 4.15 Grouping of SQL Statements  
### 4.16 The Catalog Tables  
### 4.17 Retrieving Errors and Warnings  
### 4.18 Definitions of SQL Statements 
# PART II Querying and Updating Data  
## CHAPTER 5 SELECT Statement: Common Elements
### 5.1 Introduction 
### 5.2 Literals and Their Data Types
### 5.3 Expressions 
### 5.4 Assigning Names to Result Columns 
### 5.5 The Column Specification 
### 5.6 The User Variable and the SET Statement 
### 5.7 The System Variable 
### 5.8 The Case Expression 
### 5.9 The Scalar Expression Between Brackets 
### 5.10 The Scalar Function 
### 5.11 Casting of Expressions 
### 5.12 The Null Value as an Expression 
### 5.13 The Compound Scalar Expression 
### 5.14 The Aggregation Function and the Scalar Subquery 
### 5.15 The Row Expression 
### 5.16 The Table Expression 
### 5.17 Answers  
## CHAPTER 6 SELECT Statements, Table Expressions, and Subqueries 
### 6.1 Introduction 
### 6.2 The Definition of the SELECT Statement 
### 6.3 Processing the Clauses in a Select Block 
### 6.4 Possible Forms of a Table Expression 
### 6.5 What Is a SELECT Statement? 
### 6.6 What Is a Subquery? 
### 6.7 Answers 
## CHAPTER 7 SELECT Statement:The FROM Clause  
### 7.1 Introduction  
### 7.2 Table Specifications in the FROM Clause  
### 7.3 Again, the Column Specification 
### 7.4 Multiple Table Specifications in the FROM Clause  
### 7.5 Pseudonyms for Table Names 
### 7.6 Various Examples of Joins 
### 7.7 Mandatory Use of Pseudonyms   
### 7.8 Tables of Different Databases              
### 7.9 Explicit Joins in the FROM Clause 
### 7.10 Outer Joins  
### 7.11 The Natural Join  
### 7.12 Additional Conditions in the Join Condition 
### 7.13 The Cross Join 
### 7.14 Replacing Join Conditions with USING 
### 7.15 The FROM Clause with Table Expressions   
### 7.16 Answers   

## CHAPTER 8 SELECT Statement: The WHERE Clause  
### 8.1 Introduction  
### 8.2 Conditions Using Comparison Operators   
### 8.3 Comparison Operators with Subqueries   
### 8.4 Comparison Operators with Correlated Subqueries 
### 8.5 Conditions Without a Comparison Operator 
### 8.6 Conditions Coupled with AND, OR, XOR, and NOT  
### 8.7 The IN Operator with Expression List 
### 8.8 The IN Operator with Subquery  
### 8.9 The BETWEEN Operator  
### 8.10 The LIKE Operator  
### 8.11 The REGEXP Operator  
### 8.12 The MATCH Operator  
### 8.13 The IS NULL Operator  
### 8.14 The EXISTS Operator  
### 8.15 The ALL and ANY Operators   
### 8.16 Scope of Columns in Subqueries                
### 8.17 More Examples with Correlated Subqueries  
### 8.18 Conditions with Negation 
### 8.19 Answers   

## CHAPTER 9 SELECT Statement: SELECT Clause and Aggregation Functions   
### 9.1 Introduction  
### 9.2 Selecting All Columns (*)  
### 9.3 Expressions in the SELECT Clause   
### 9.4 Removing Duplicate Rows with DISTINCT 
### 9.5 When Are Two Rows Equal? 
### 9.6 More Select Options 
### 9.7 An Introduction to Aggregation Functions 
### 9.8 COUNT Function  
### 9.9 MAX and MIN Functions  
### 9.10 The SUM and AVG Function 
### 9.11 The VARIANCE and STDDEV Functions 
### 9.12 The VAR_SAMP and STDDEV_SAMP Functions   
### 9.13 The BIT_AND, BIT_OR, and BIT_XOR Functions   
### 9.14 Answers   

## CHAPTER 10 SELECT Statement: The GROUP BY Clause   
### 10.1 Introduction  
### 10.2 Grouping on One Column  
### 10.3 Grouping on Two or More Columns     
### 10.4 Grouping on Expressions  
### 10.5 Grouping of Null Values             
### 10.6 Grouping with Sorting  
### 10.7 General Rules for the GROUP BY Clause  
### 10.8 The GROUP_CONCAT Function  
### 10.9 Complex Examples with GROUP BY 
### 10.10 Grouping with WITH ROLLUP  
### 10.11 Answers

## CHAPTER 11 SELECT Statement: The HAVING Clause   
### 11.1 Introduction  
### 11.2 Examples of the HAVING Clause   
### 11.3 A HAVING Clause but not a GROUP BY Clause  
### 11.4 General Rule for the HAVING Clause  
### 11.5 Answers   

## CHAPTER 12 SELECT Statement: The ORDER BY Clause   
### 12.1 Introduction  
### 12.2 Sorting on Column Names  
### 12.3 Sorting on Expressions  
### 12.4 Sorting with Sequence Numbers                   
### 12.5 Sorting in Ascending and Descending Order  
### 12.6 Sorting Null Values 
### 12.7 Answers   

## CHAPTER 13 SELECT Statement: The LIMIT Clause 
### 13.1 Introduction  
### 13.2 Get the Top…  
### 13.3 Subqueries with a LIMIT Clause  
### 13.4 Limit with an Offset  
### 13.5 The Select Option SQL_CALC_FOUND_ROWS                 
### 13.6 Answers   

## CHAPTER 14 Combining Table Expressions  
### 14.1 Introduction  
### 14.2 Combining with UNION 
### 14.3 Rules for Using UNION   
### 14.4 Keeping Duplicate Rows 
### 14.5 Set Operators and the Null Value 
### 14.6 Answers   

## CHAPTER 15 The User Variable and the SET Statement  
### 15.1 Introduction  
### 15.2 Defining Variables with the SET Statement   
### 15.3 Defining Variables with the SELECT Statement  
### 15.4 Application Areas for User Variables   
### 15.5 Life Span of User Variables  
### 15.6 The DO Statement  
### 15.7 Answers  
 
## CHAPTER 16 The HANDLER Statement 
### 16.1 Introduction  
### 16.2 A Simple Example of the HANDLER Statement  
### 16.3 Opening a Handler  
### 16.4 Browsing the Rows of a Handler   
### 16.5 Closing a Handler 
### 16.6 Answers   

## CHAPTER 17 Updating Tables  
### 17.1 Introduction  
### 17.2 Inserting New Rows   
### 17.3 Populating a Table with Rows from Another Table           
### 17.4 Updating Values in Rows   
### 17.5 Updating Values in Multiple Tables   
### 17.6 Substituting Existing Rows  
### 17.7 Deleting Rows from a Table  
### 17.8 Deleting Rows from Multiple Tables 
### 17.9 The TRUNCATE Statement                  
### 17.10 Answers    

## CHAPTER 18 Loading and Unloading Data   
### 18.1 Introduction  
### 18.2 Unloading Data  
### 18.3 Loading Data
  
## CHAPTER 19 Working with XML Documents  
### 19.1 XML in a Nutshell  
### 19.2 Storing XML Documents   
### 19.3 Querying XML Documents  
### 19.4 Querying Using Positions  
### 19.5 The Extended Notation of XPath  
### 19.6 XPath Expressions with Conditions   
### 19.7 Changing XML Documents 

# PART III  Creating Database Objects 

## CHAPTER 20 Creating Tables  
### 20.1 Introduction  
### 20.2 Creating New Tables 
### 20.3 Data Types of Columns   
### 20.4 Adding Data Type Options 
### 20.5 Creating Temporary Tables              
### 20.6 What If the Table Already Exists?  
### 20.7 Copying Tables  
### 20.8 Naming Tables and Columns  
### 20.9 Column Options: Default and Comment  
### 20.10 Table Options 
### 20.11 The CSV Storage Engine  
### 20.12 Tables and the Catalog 
### 20.13 Answers   

## CHAPTER 21 Specifying Integrity Constraints 
### 21.1 Introduction  
### 21.2 Primary Keys 
### 21.3 Alternate Keys 
### 21.4 Foreign Keys  
### 21.5 The Referencing Action 
### 21.6 Check Integrity Constraints   
### 21.7 Naming Integrity Constraints               
### 21.8 Deleting Integrity Constraints 
### 21.9 Integrity Constraints and the Catalog                  
### 21.10 Answers 
  
## CHAPTER 22 Character Sets and Collations  
### 22.1 Introduction  
### 22.2 Available Character Sets and Collations 
### 22.3 Assigning Character Sets to Columns 
### 22.4 Assigning Collations to Columns  
### 22.5 Expressions with Character Sets and Collations 
### 22.6 Sorting and Grouping with Collations  
### 22.7 The Coercibility of Expressions 
### 22.8 Related System Variables  
### 22.9 Character Sets and the Catalog  
### 22.10 Answers   

## CHAPTER 23 The ENUM and SET Types   
### 23.1 Introduction  
### 23.2 The ENUM Data Type   
### 23.3 The SET Data Type  
### 23.4 Answers  
 
## CHAPTER 24 Changing and Dropping Tables  
### 24.1 Introduction  
### 24.2 Deleting Entire Tables 
### 24.3 Renaming Tables   
### 24.4 Changing the Table Structure  
### 24.5 Changing Columns  
### 24.6 Changing Integrity Constraints 
### 24.7 Answers   

## CHAPTER 25 Using Indexes  
### 25.1 Introduction  
### 25.2 Rows, Tables, and Files 
### 25.3 How Does an Index Work? 
### 25.4 Processing a SELECT Statement: The Steps  
### 25.5 Creating Indexes  
### 25.6 Defining Indexes Together with the Tables  
### 25.7 Dropping Indexes  
### 25.8 Indexes and Primary Keys  
### 25.9 The Big PLAYERS_XXL Table   
### 25.10 Choosing Columns for Indexes 
### 25.11 Indexes and the Catalog  
### 25.12 Answers   

## CHAPTER 26 Views   
### 26.1 Introduction  
### 26.2 Creating Views  
### 26.3 The Column Names of Views  
### 26.4 Updating Views: WITH CHECK OPTION 
### 26.5 Options of Views   
### 26.6 Deleting Views   
### 26.7 Views and the Catalog   
### 26.8 Restrictions on Updating Views  
### 26.9 Processing View Statements  
### 26.10 Application Areas for Views  
### 26.11 Answers   

## CHAPTER 27 Creating Databases 
### 27.1 Introduction  
### 27.2 Databases and the Catalog 
### 27.3 Creating Databases         
### 27.4 Changing Databases 
### 27.5 Dropping Databases 

## CHAPTER 28 Users and Data Security  
### 28.1 Introduction  
### 28.2 Adding and Removing Users                
### 28.3 Changing the Names of Users   
### 28.4 Changing Passwords           
### 28.5 Granting Table and Column Privileges  
### 28.6 Granting Database Privileges  
### 28.7 Granting User Privileges  
### 28.8 Passing on Privileges: WITH GRANT OPTION           
### 28.9 Restricting Privileges 
### 28.10 Recording Privileges in the Catalog                 
### 28.11 Revoking Privileges  
### 28.12 Security of and Through Views  
### 28.13 Answers  
 
## CHAPTER 29 Statements for Table Maintenance   
### 29.1 Introduction  
### 29.2 The ANALYZE TABLE Statement   
### 29.3 The CHECKSUM TABLE Statement  
### 29.4 The OPTIMIZE TABLE Statement 
### 29.5 The CHECK TABLE Statement  
### 29.6 The REPAIR TABLE Statement  
### 29.7 The BACKUP TABLE Statement  
### 29.8 The RESTORE TABLE Statement
  
## CHAPTER 30 The SHOW, DESCRIBE, and HELP Statements 
### 30.1 Introduction  
### 30.2 Overview of SHOW Statements  
### 30.3 Additional SHOW Statements  
### 30.4 The DESCRIBE Statement   
### 30.5 The HELP Statement   

# PART IV Procedural Database Objects 

## CHAPTER 31 Stored Procedures 
### 31.1 Introduction  
### 31.2 An Example of a Stored Procedure  
### 31.3 The Parameters of a Stored Procedure  
### 31.4 The Body of a Stored Procedure 
### 31.5 Local Variables  
### 31.6 The SET Statement  
### 31.7 Flow-Control Statements  
### 31.8 Calling Stored Procedures   
### 31.9 Querying Data with SELECT INTO 
### 31.10 Error Messages, Handlers, and Conditions      
### 31.11 Retrieving Data with a Cursor 
### 31.12 Including SELECT Statements Without Cursors  
### 31.13 Stored Procedures and User Variables   
### 31.14 Characteristics of Stored Procedures  
### 31.15 Stored Procedures and the Catalog   
### 31.16 Removing Stored Procedures  
### 31.17 Security with Stored Procedures  
### 31.18 Advantages of Stored Procedures 

## CHAPTER 32 Stored Functions 
### 32.1 Introduction  
### 32.2 Examples of Stored Functions   
### 32.3 More on Stored Functions  
### 32.4 Removing Stored Functions

## CHAPTER 33 Triggers 
### 33.1 Introduction  
### 33.2 An Example of a Trigger  
### 33.3 More Complex Examples   
### 33.4 Triggers as Integrity Constraints 
### 33.5 Removing Triggers   
### 33.6 Triggers and the Catalog   
### 33.7 Answers   

## CHAPTER 34 Events 
### 34.1 What Is an Event? 
### 34.2 Creating Events 
### 34.3 Properties of Events  
### 34.4 Changing Events 
### 34.5 Removing Events   
### 34.6 Events and Privileges         
### 34.7 Events and the Catalog 

# PART V Programming with SQL 
                  
## CHAPTER 35 MySQL and PHP 
### 35.1 Introduction  
### 35.2 Logging On to MySQL  
### 35.3 Selecting a Database   
### 35.4 Creating an Index  
### 35.5 Retrieving Error Messages   
### 35.6 Multiple Connections Within One Session  
### 35.7 SQL Statements with Parameters  
### 35.8 SELECT Statement with One Row   
### 35.9 SELECT Statement with Multiple Rows  
### 35.10 SELECT Statement with Null Values  
### 35.11 Querying Data About Expressions  
### 35.12 Querying the Catalog  
### 35.13 Remaining MYSQL Functions 
 
## CHAPTER 36 Dynamic SQL with Prepared Statement 
### 36.1 Introduction  
### 36.2 Working with Prepared SQL Statements   
### 36.3 Prepared Statements with User Variables 
### 36.4 Prepared Statements with Parameters  
### 36.5 Prepared Statements in Stored Procedures  
 
## CHAPTER 37 Transactions and Multiuser Usage 
### 37.1 Introduction  
### 37.2 What Is a Transaction?  
### 37.3 Starting Transactions  
### 37.4 Savepoints     
### 37.5 Stored Procedures and Transactions   
### 37.6 Problems with Multiuser Usage   
### 37.7 Locking  
### 37.8 Deadlocks 
### 37.9 The LOCK TABLE and UNLOCK TABLE Statements   
### 37.10 The Isolation Level   
### 37.11 Waiting for a Lock          
### 37.12 Moment of Processing Statements  
### 37.13 Working with Application Locks  
### 37.14 Answers    
 
# APPENDIX A Syntax of SQL  
## A.1 Introduction  
## A.2 The BNF Notation  
## A.3 Reserved Words in SQL  
## A.4 Syntax Definitions of SQL Statements  

# APPENDIX B Scalar Functions  

# APPENDIX C System Variables  

# APPENDIX D Bibliography  
  