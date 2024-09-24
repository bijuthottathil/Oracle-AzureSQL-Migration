# oracletoazuresqlmigration
Intend of this repository is to show case migration of oracle tables to Azure SQL using SQL Server Migration Assistant for Oracle


My Source Database is Oracle 21 configured in my personal laptop. I have schema called myuser and few tables available to migrate to Azure SQL

![image](https://github.com/user-attachments/assets/db16a3e5-c163-4f1a-8177-fd54656fcbad)

I will focusing to migrate below 2 tables from myuser schema to Azure sql

![image](https://github.com/user-attachments/assets/d93eebdb-d554-404f-8a03-372416ff6d46)


My Destination Database is Azure SQL configured in my Azure Subscription

![image](https://github.com/user-attachments/assets/2ac901b0-bd27-495c-8d0a-37d94977cdfb)

I will be using SQL Database to migrate tables from Oracle

![image](https://github.com/user-attachments/assets/8fa4c95d-dbac-459b-80fa-bfa41a5242b0)

![image](https://github.com/user-attachments/assets/63f5952b-9c09-4be5-813b-e8dbd6471ae0)

There are many table available in this database

![image](https://github.com/user-attachments/assets/98d2bc22-503c-4384-b52c-98cdd4682450)

![image](https://github.com/user-attachments/assets/d2e4135a-92e1-44c1-abd5-9fff461d3471)

 I am using  SQL Server Migration Assistant  for this migration

 ![image](https://github.com/user-attachments/assets/f8eb0e6a-886a-4c64-bffc-db43f2a20d68)

Creating a migration project and Connecting to source and destination databases 
![image](https://github.com/user-attachments/assets/80c5b7d5-a8b1-4c39-a676-1b2845eee2c9)


![image](https://github.com/user-attachments/assets/472d7c2a-4c81-4c09-a484-4463b1ec9c27)

Selected only 2 tables from Myuser Schema
![image](https://github.com/user-attachments/assets/0bb1f447-8e3d-4a57-aeba-6b3178991b32)


![image](https://github.com/user-attachments/assets/925639b4-24ce-4130-9209-d5f829068441)

Generate a report 

Report looks good. 

![image](https://github.com/user-attachments/assets/6c5fd614-5293-4dd5-b067-4b2a6b394516)

Then

Connect to destination Azure SQL Db

![image](https://github.com/user-attachments/assets/67888011-d5b9-4c44-9fa1-4762a8a27755)

Convert schema now

![image](https://github.com/user-attachments/assets/cee0cbe1-0129-4399-92b0-8bd392d8d612)

In destination DB, you can see schema is updated

![image](https://github.com/user-attachments/assets/4da2d9e6-c209-4867-8623-f9c63dfd4fda)

Next you can migrate table data by clicking "migrate data" option


![image](https://github.com/user-attachments/assets/00ea3661-0ab5-4a72-a971-b50c6fe8d005)



![image](https://github.com/user-attachments/assets/2dc4815e-ac33-481f-b977-70eb8749af84)

![image](https://github.com/user-attachments/assets/fdda65f2-2668-4227-894a-d785d3dc864c)

Both tables are migrated to Azure SQL Successfully


![image](https://github.com/user-attachments/assets/aeaf2220-c31d-4024-a64f-a60b7bb27099)


![image](https://github.com/user-attachments/assets/4affa70a-22ba-4728-8571-65c55c8f7f59)

![image](https://github.com/user-attachments/assets/c8945d88-2373-451d-ade0-c6ea14d7c1b1)


Both tables are succesfully migrated

# Happy coding


