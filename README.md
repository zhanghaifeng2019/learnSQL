# ---在线导入数据库，用来做练习。

1，官网上(  https://dev.mysql.com/doc/index-other.html  )  下载数据库（world database),并解压到桌面的data文件夹下。

2,打开数据库
   mysql -u ユーザー名 -p
   Enter password:*********

3，用 SOURCE+路径 来导入数据库。
   mysql> SOURCE C:\Users\zhang\Desktop\data\world.sql;

4,show databases;

5,use world;

这样就可以使用了。


------------------------------------------------------------------------------------------------------------


xampp里面使用mysql数据库

1，	打开xampp，启动shell

 2，输入mysqladmin -u root password "no744634" 回车
  
 3，xampp文件夹下，的  phpMyAdmin\config.inc.php 文件
 
 4，$cfg['Servers'][$i]['password']="no744634"  保存
 
 5，コマンドプロンプトを起動する  或者直接在xampp的shell里面输入
 
    c:\xampp\mysql\bin
 6,mysql -u root -p 
 
 7,输入密码 no744634


