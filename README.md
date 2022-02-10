# DBMS-Lab

## MySql Basics Comments:

### SHOW DATABASES

```SHOW DATABASES;```

+--------------------+
| Database           |
+--------------------+
| Learning           |
| information_schema |
| library            |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
6 rows in set (0.00 sec)

### CREATE DATABASE

```CREATE DATABASE Pvr_Cinemas;```

```SHOW DATABASES;```

+--------------------+
| Database           |
+--------------------+
| Learning           |
| Pvr_Cinemas        |
| information_schema |
| library            |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
7 rows in set (0.01 sec)

### USE DATABASE

```USE Pvr_Cinemas```

Database changed


### SHOW TABLE

```SHOW TABLES```

Empty set (0.01 sec)

### CREATE TABLE

```CREATE TABLE userdetails(User_Id int primary key auto_increment NOT NULL, Username varchar(20) NOT NULL, Email varchar(255) UNIQUE NOT NULL);```

Query OK, 0 rows affected (0.05 sec)

```SHOW TABLES```

+-----------------------+
| Tables_in_Pvr_Cinemas |
+-----------------------+
| userdetails           |
+-----------------------+
1 row in set (0.01 sec)



