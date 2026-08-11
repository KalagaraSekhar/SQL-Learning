## Creating the database
CREATE DATABASE employees;

## Creating the tables
1) Student_info:-
   *Creating;
   CREATE TABLE student_info(
student_id int,
student_name varchar(255),
student_address varchar(255),
student_city varchar(255)
);

    *Altering;
   ALTER TABLE student_info
ADD COLUMN student_email varchar(255);

   *Inserting;
   INSERT INTO student_info
VALUES(100,"Sekhar","Nuzvid","Vijayawada","xxxx@gmail.com");
SELECT *FROM student_info;

  *Retrieving the data;
  SELECT *FROM student_info

  2) employees:-
     *Creating;
     CREATE TABLE employees(
emp_id int,
emp_name varchar(255),
branch_name varchar(255),
dept varchar(255),
sector int
);

  *Altering;
  ALTER TABLE employees
ADD PRIMARY KEY (emp_id);

  *Inserting;
  INSERT INTO employees
VALUES(1,"Sekhar","CSE","HR",5),
(2,"Raman","ECE","Front Office",6),
(3,"Hari","AIDS","Logistics",17),
(4,"Bhuvanesh","CSE-3","Management",9),
(5,"Anish","Mechanical","Sales",10);

  *Retrieving the data;
  SELECT *from employees ORDER BY dept ASC; --(Specifically arrange the data in ascending order by the dept column(data))

  ** These are the queries I have practiced in the SQL Part-2 Learning.
 
