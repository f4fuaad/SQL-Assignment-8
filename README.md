# SQL-Assignment-8
Q-1. Write an SQL query to fetch intersecting records of two tables.

Ans  select  idno, salary
         from emp_table ET inner join 
        worker_table WT on ET.idno = WT.idno

Q-2. Write an SQL query to show records from one table that another table does not
have.
Ans  select  idno, salary
         from emp_table ET left join 
        worker_table WT on ET.idno = WT.idno
