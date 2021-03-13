# Dump-a-specific-table-or-few-rows-MySQL-
Dump a specific table or few rows (MySQL)
https://sysgears.com/notes/dump-a-specific-table-or-few-rows-mysql/



--passwprd=1234
mysqldump -u root -p dbtest tb_test --where="bln='September 2020'" -r "C:\users\User\Desktop\MySql\tb_test_September2020.sql"
