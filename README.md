##Simple_DataBase_For_Testing
##一个用来做测试用的数据库

没什么特别的，就是一个SQL文件，建立五张表，然后插一些数据，做这个东西的目的是为了练习或者测试SQL用的。这个SQL语法是基于MySQL的，至于表结构如下。

###T1

| ID     | Name        | Num     | Date1 | Date2 | Status     |
| ------ | ----------- | ------- | ----- | ----- | ---------- |
| int(11)| varchar(50) | int(11) | date  | date  | tinyint(4) |


###T2

| ID     | T1_ID   | Name        | Num     | Date1 | Date2 | Status     |
| ------ | ------- | ----------- | ------- | ----- | ----- | ---------- |
| int(11)| int(11) | varchar(50) | int(11) | date  | date  | tinyint(4) |


###T3

| ID     | T1_ID   | T2_ID   | Name        | Num     | Date1 | Date2 | Status     |
| ------ | ------- | ------- | ----------- | ------- | ----- | ----- | ---------- |
| int(11)| int(11) | int(11) | varchar(50) | int(11) | date  | date  | tinyint(4) |


###T4

| ID     | T3_ID   | Name        | Num     | Date1 | Date2 | Status     |
| ------ | ------- | ----------- | ------- | ----- | ----- | ---------- |
| int(11)| int(11) | varchar(50) | int(11) | date  | date  | tinyint(4) |


###T5

| ID     | T1_ID   | T2_ID   | T3_ID   | T4_ID   | Name        | Num     | Date1 | Date2 | Status     |
| ------ | ------- | ------- | ------- | ------- | ----------- | ------- | ----- | ----- | ---------- |
| int(11)| int(11) | int(11) | int(11) | int(11) | varchar(50) | int(11) | date  | date  | tinyint(4) |