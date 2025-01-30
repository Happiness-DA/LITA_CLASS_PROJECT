# LITA_CLASS_PROJECT
Projects undertaken during my data analysis training at the Incubator Hub
### Project Title: Introduction to Excel
##### Microsoft Excel is a spreadsheet program that allows users to organize, format, calculate, store, sort, and manipulate data. Although Excel is not a database, it is often used in data analytics to assess large amounts of information and create visualizations.

### Project Overview 
##### Excel for Data Analysis: Here excel program is used in the process of data analysis to carry out numerous activities like data extraction, data cleaning and lots more. 

### Data Sources
##### The data used were provided by the facilitators. The data files includes excel files and csv. files.
### Tool Used
- Microsoft Excel 
    1.  For Data Cleaning
    3.  Data Visualization
## Data Cleaning and Preparation
  To carry out an analysis using any data, it is necessary to ensure the data is properly cleaned. Cleaning a data involves changing data types, creating / deleting columns, elimination of blank spaces, incorrect, and outdated information. 
### Data Formatiing
During the process of data cleaning it is necessary to also format the data. This entails text alignment, color, font, cell background color, images and many others.

#### Functions used in excel
- Aggregate Functions: they are used to calculate the sum and the arithmethic mean of a range of numbers (the sum and average function). E.g =SUM(A1:A10) adds the values in cells A1 through A10. Other aggregate functions are COUNT, MAX, MIN which counts the number of cells in a range that contain numbers, finds the maximum value in a set of values, finds the minimum value in a set of values respectively.
- Text functions: they include the UPPER, LOWER, PROPER functions and they are used convert any text string to uppercase, to lowercase and to proper case, i.e., the first letter in each word will be in uppercase, and all the other will be in lowercase respectively. Other text functions are LEFT, MID, RIGHT functions which are used to extract specific parts of a string of text. 
    Other functions includes: TRIM, RANDBETWEEN, CONCATENATE.

#### Reporting with Pivot table in Excel
Excel's pivot tables are a useful tool for reporting because they can summarize large amounts of data to generate insights and reports.Pivot tables allow users to quickly and easily summarize data, create interactive dashboards and generate reports efficiently.
#### Examples of Excel Projects

![Screenshot 2024-11-05 122702](https://github.com/user-attachments/assets/1158e403-1928-4022-aaaf-f31f229885e4)

![Screenshot 2024-11-05 122901](https://github.com/user-attachments/assets/b20e3f8d-af13-4da8-afa9-d7a19d212032)

![Screenshot 2024-11-05 122922](https://github.com/user-attachments/assets/ae4c010b-9f45-4886-9729-56f177ee54af)

![Screenshot 2024-11-05 123307](https://github.com/user-attachments/assets/95201d46-02e7-4f77-b96e-d920c2aa0680)
![Screenshot 2024-11-05 123324](https://github.com/user-attachments/assets/3571a8ee-671b-4932-9859-7b64c59cfb6c)


### Project Title: Introduction to Structured Query Language
##### Structured Query Language is a domain-specific language used to manage data, especially in a relational database management system. It is particularly useful in handling structured data, i.e., data incorporating relations among entities and variables.
  ### Project Overview 
##### SQL for Data Analysis: Here SQL serves as a gateway to structured data, enabling users to retrieve, transform, and explore datasets.
### Data Sources
##### The data used were provided by the facilitators. The data files includes tables created on the Database and csv. files.

### Tool Used
- Structured Query Language(SQL) 
    1.  For Data Extraction
    2.  For Data Visualization
## Data Extraction
Using appropriate queries, data could be extracted from files containing long rows and columns of data.

#### Statements used in SQL
These SQL commands are mainly categorized into five categories
DDL – Data Definition Language.
DQL – Data Query Language.
DML – Data Manipulation Language.
DCL – Data Control Language.
TCL – Transaction Control Language
- SELECT: The SQL SELECT statement is used to query and retrieve data from a database. SELECT is one of the most commonly used SQL statements, allowing you to select specific columns and rows of data from database objects.
-  INSERT: Adds new data (rows) to a table.
-  CREATE: It is used to cretae a new table in the database.
-   ALTER: It is used to alter the structure of the databse.
  Other commands includes; ORDERBY, GROUPBY, UPDATE, HAVING, TRUNCATE, DELETE, GRANT, REVOKE and many more.
each of these commands are unique and play different roles in operating SQL.

#### Examples of SQL Commands and their outcomes 
|SQL Command|Result|
|---------|---------|
|select * from Employee|Returns the table employee with all the columns|
|drop table Employee|Deletes the table structure and record|
|delete from Employee where staffid = 'AB212'|deletes the record for the specified staffid|
|select SUM(salary) AS TOTALSALARY FROM Salary|returns the totalsalary|
|update salary set Salary = 7059436.8870 where Staffid = 'AB401'|changes the salary for 'AB401' to 7059436.8870|


### Project Title: Introduction to PowerBI
##### Power BI is a business analytics tool that helps users transform data into insights and make data-driven decisions. Power BI is a data visualization platform used primarily for business intelligence purposes. Power BI stands for Power Business Intelligence and refers to a set of software tools and connectors that help you transform data from multiple sources into actionable insights.

### Project Overview 
##### Power BI: Here Power BI is employed in data visualization to summarize data and report for interactive analysis.
### Data Sources
##### The data used were provided by the facilitators. The data files includes Excel files and tables created.

### Tool Used
-Microsoft Power BI
    1.  For Data Visualization
    2.  For Reporting
    
## Data Visualization
During data analysis files are imported into power BI and they are transformed. This process is called "ETL" meaning extract, transform and load. During the process of transformation data type is changed, empty columns are removed and the column quality, distribution and profile are also checked. After transformation the data is loaded to analyze.

## Reporting
Reporting in PowerBI involves the use of tables, matrix, cards, slicers, pie charts, donut charts, histograms, barcharts e.t.c to summarize the data making it interactive and appealing to the eyes. The goal of reporting is to make the data easily understandable. 

#### Examples of PowerBI Projects

![Screenshot 2024-11-05 122157](https://github.com/user-attachments/assets/309a39f6-532b-4bdb-a45a-e29e7e0db051)

![Screenshot 2024-11-05 122210](https://github.com/user-attachments/assets/f4bdbe2e-8337-4ac1-aa3a-9d5b322a232d)

![Screenshot 2024-11-05 122240](https://github.com/user-attachments/assets/64a2e843-201a-411b-bfaa-bb3529406daa)

![Screenshot 2024-11-05 122222](https://github.com/user-attachments/assets/ddc8f40a-3a22-467f-b463-8b91e1db08ec)

![Screenshot 2024-11-05 122337](https://github.com/user-attachments/assets/6464fdfb-7fb6-4f5c-9b7a-933d77ae50ca)
