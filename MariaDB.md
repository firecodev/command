# MariaDB

**References**

[SQL Statements & Structure - MariaDB Knowledge Base](https://mariadb.com/kb/en/sql-statements-structure/)

#### Drop if exist

```
DROP DATABASE IF EXISTS db_name;
```

#### Create database

```
CREATE DATABASE db_name CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

#### Create user

```
CREATE USER 'username'@'%' IDENTIFIED BY 'password';
```

#### Grant privilege

```
GRANT ALL PRIVILEGES ON *.* TO 'username'@'%';
```

#### Flush privilege

```
FLUSH PRIVILEGES;
```
