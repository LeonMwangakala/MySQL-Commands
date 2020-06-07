# [7] To insert data in the existing table.  
<b>Syntax:</b>  
> INSERT INTO < TableName >   
VALUES(column1value,column2value, column3value, column4value, column5value) ;    

<b>Example 1 (Inserting Single Row of values):</b>
>  INSERT INTO < TableName >   
VALUES(1,"Saurav","Kumar",11,"2001-01-01","A") ;  
    
<b>Example 2 (Inserting more than one row simultaneously):</b>
>  INSERT INTO Students2   
VALUES(2,"Saurav","Kumar",34,"2001-01-01","A") ,  
(3,"Viswesraya","Kishore",3,"2000-01-02","B") ,  
(4,"Samantha","Kumari",4,"2002-01-03","C") ;    
  
<b>Example 3 (Inserting data in Specific Columns Only):</b>
>  INSERT INTO Students2 (first_name, last_name, roll_number) VALUES("Krishna","Kumar",10) ;  
  
   
