# MySQL Cheat Sheet

This Mysql cheat sheet provides a quick overview of sql commands to interact with a MySQL database. It can't cover every edge case, so if you need mroe information about any of these elements, refer to the offical site.

## Table of Contents

-   [General](#General)
-   [Database Management](#Database-Management)

## General

-   Commands are not case senitive, but usually **CAPITALIZE** all SQL keywords, and name of tables, columns, etc are lowercase words.
-   Use `;` as a command end marker

### Add Mysql to your PATH

Once you've downloaded and start up the Mysql server, add the following line to your `./bash_profile` or `.zshrc` file

```bash
export PATH=\${PATH}:/usr/local/mysql/bin/
```

Then if you need to reload `./bash_profile`, try:

```bash
source ~/.bash_profile
```

### Start/Stop/Restart the server

```bash
mysql.server start
mysql.server stop
mysql.server restart
```

### Login in As Root

Login in as root (password is prompted):

```bash
mysql -u root -p
```

### Quit

```sql
exit
```

## Database Management

#### Show all databases

```sql
SHOW DATABASES;
```

#### Create/Delete a database

```sql
CREATE DATABASE <databaseName>;

DROP DATABASE <databaseName>;
```

#### Select Database

```sql
USE <databse>;
```

#### Determin what database is in use

```sql
SELECT DATABASE();
```

### Grant All Preiveleges on Selected Databases

```sql
GRANT ALL PRIVILEGES ON <databaseName>.* TO '<userName>'@'<host>';
FLUSH PRIVILEGES;
```

### Remove Grants

```sql
REVOKE ALL PRIVILEGES ON <databaseName>.* TO '<userName>'@'<host>';
FLUSH PRIVILEGES;
```

### Show Privileges

```sql
SHOW GRANTS FOR '<userName>'@'<host>';
```

## Table Look Around

### Show all tables

```sql
SHOW TABLES;
```

### Show Table Properties

```sql
DESCRIBE <tableName>;
```
