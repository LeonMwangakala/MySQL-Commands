# [5] To create a new Table.  
<b>Syntax:</b>  
> CREATE TABLE < TableName >   
(  
< columnName1 > < column1DataType > < optionalContraints >,  
< columnName2 > < column2DataType > < optionalContraints >,  
< columnName3 > < column3DataType > < optionalContraints >,  
< columnName4 > < column4DataType > < optionalContraints >,  
< columnName5 > < column5DataType > < optionalContraints >,  
) ;  

<b>Example 1 (Table Without Constraints):</b>
> CREATE TABLE Students1   
(  
id INT ,  
first_name VARCHAR(100),  
last_name VARCHAR(100),  
roll_number INT,  
dob DATE,   
section VARCHAR(1)     
) ;  
  
<b>Example 2 (Table WITH Constraints):</b>
> CREATE TABLE Students2   
(  
id INT NOT NULL AUTO_INCREMENT UNIQUE,  
first_name VARCHAR(100) NOT NULL ,  
last_name VARCHAR(100) NOT NULL ,  
roll_number INT UNIQUE,  
dob DATE DEFAULT='2001-01-01',   
section VARCHAR(1) DEFAULT='A',   
PRIMARY KEY(id)      
) ;  
  
   
