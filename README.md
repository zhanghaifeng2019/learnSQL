# ---在线导入数据库，用来做练习。

1，官网上(https://dev.mysql.com/doc/index-other.html)下载数据库（world database),并解压到桌面的data文件夹下。

2,打开数据库
   mysql -u ユーザー名 -p
   Enter password:*********

3，用 SOURCE+路径 来导入数据库。
   mysql> SOURCE C:\Users\zhang\Desktop\data\world.sql;

4,show databases;

5,use world;

这样就可以使用了。
