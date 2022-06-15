```
$ sudo su - postgres                                                        ─╯
postgres@vietthan-linux:~$ psql
psql (14.3 (Ubuntu 14.3-1.pgdg20.04+1))
Type "help" for help.

postgres=# \l
postgres=# CREATE DATABASE test;
CREATE DATABASE
postgres=# CREATE USER viett
postgres-# ;
CREATE ROLE
postgres=# ALTER USER viett WITH ENCRYPTED PASSWORD 'postgres';
ALTER ROLE
postgres=# GRANT ALL PRIVILEGES ON DATABASE test TO viett;
GRANT
```

^ above defaults to create database `test` at localhost:5432