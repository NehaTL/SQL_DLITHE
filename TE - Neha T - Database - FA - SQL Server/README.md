## **INTRODUCTION TO SQL, SSIS, SSRS, IICS**

### **OVERVIEW**

#### **SQL**
It stands for Structured Query Language. This language is used to create, manipulate, delete, store, fetch the data from database. SQL Server, Oracle, MySQL, Postgress are some of the database connections.

#### **SSIS**
It stands for SQL Server Integration Services. This is an ETL tool that perform Extract, Transform and Load. It is mainly used to solve complex business requirements by Extracting files from different locations may be in any format, performing data transformations if required like aggregate, union, SCDs, etc. and loading it to the different locations. Multiple source files can be loaded into single target file or vice versa.

#### **SSRS**
It stands for SQL Server Reporting Services. This allows creations of tables, graphical reports making user understand the business senario easy. Reports can be downloaded in Word, EXcel, PPT, PDF, TIFF file, MHTML (web archive), CSV (common delimited), XML file with report data.

#### **IICS**
It stands for Informatica Intelligent Cloud Services. Integrate cloud based data with the data residing in on-premise databases and systems or between cloud applications. Basically it is used to perform extraction, transformation and Load the cloud based data. 

### **TASKS**

#### **SQL**
 
 **DDL - Data Definition Language**
 
    CREATE - Used to create tables or views.
    ALTER - Used to modify the table contents.
    DROP - Used to delete the tables or views.
    
 **DML - Data Manipulation Language**
  
    INSERT - Inserts values or rows to the tables.
    UPDATE - Modifies the table accordingly.
    DELETE - Delete contents in tables.
    
 **DQL - Data Query Language**
  
    SELECT - Retrieve the tables.
    
 **NORMALIZATION**
  
    1NF - A table cannot have Multi values in single row. Split the rows into two if there multi values in the single row to satisfy 1NF Rule.
    2NF - It should be in INF. Remove partial dependency to Satisfy 2NF.
    3NF - A table should be in 2NF. Remove transitive functional dependency to satisfy 3NF.
    
 **REFERENTIAL INTEGRITY**
 
     ON DELETE CASCADE ON UPDATE CASCADE 
     ON DELETE SET NULL ON UPDATE SET NULL 
     ON DELETE SET DEFAULT ON UPDATE SET DEFAULT 
 
 **RANKING**
  **ROW_NUMBER, RANK, DENSE_RANK**

    ROW_NUMBER Displays the row number.
    RANK will be ranking according to the row number leaving the gap. If there is a tie between 1st and 2nd row, it will go like 1,1,3.
    DENSE_RANK never leaves the gap. If there is a tie between 1st and 2nd row, it will go like 1,1,2.
  
 **JOINS**
  
    INNER JOIN - Returns common data from more two tables.
    LEFT JOIN - Returns all rows from left table and matching rows from right table.
    RIGHT JOIN - Returns all rows from right table and matching rows from left table.
    FULL JOIN - Returns all rows from tables regardless of matching rows.
    CROSS JOIN - Returns matrix of two tables.
  
 **VIEW**
  
    It does not store in memory but just hold table structure. Data can be modified.
  
#### **SSIS**

 **SLOWLY CHANGING DIMENSION**

    SCD1 - Can be loaded and Updated.
    SCD2 - Can be loaded and stores historical data as well.
    
 **AGGREGATE**
    
    Used to perform SUM, AVG, MIN, MAX, COUNT.
 
#### **SSRS**

    COLUMN CHART
    TABLE
  
#### **IICS**

  **SLOWLY CHANGING DIMENSION**

    SCD1 - Can be loaded and Updated.
    SCD2 - Can be loaded and stores historical data as well.
    
  **AGGREGATE**
    
    Used to perform SUM, AVG, MIN, MAX, COUNT.

  **REPLICATION**
  
    Used to replicate one or more database tables.
    Column can be removed, filtered.
    
 ### **LEARNING OBJECTIVES**
 
  **SQL** - 
    Able to write and modify the existing data.
    
  **SSIS** - 
    Be able to satisfy business requirements by automating complex transformation tasks and analyse the success and failure of the transformation process.
    
  **SSRS** - 
    Allows creation of table, deployment, manage paginated reports and can be represented graphically. It allows reports to be exported in different formats like pdf, ppt, excel, etc. 
    
  **IICS** - 
    Integrate cloud based data with the data residing in on-premise databases and systems or between cloud applications.
