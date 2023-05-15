# 数据库基本操作记录

- 登录数据库：`mysql -uroot -p` root代表账号名；


- 选择数据库名称为ebody的数据库：`use ebody;` 



- 在数据表`wp_posts`查询ID字段为5172的文章：`SELECT * FROM wp_posts where ID=5172;` 


- 显示一个表有哪些字段：`SHOW COLUMNS FROM wp_posts；` 

- 显示一个数据表的前十行数据：`SELECT * FROM wp_wppay LIMIT 10;` 

- 显示数据库中的所有数据表：`SHOW TABLES;` 