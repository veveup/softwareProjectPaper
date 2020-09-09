# 简单留言板系统

基于 SSM 框架的简单留言板系统

软件工程课程-项目

Demo
http://veveup.com:81/iboard

前端：Html+Bulma.io

框架：Spring SpringMVC MyBatis

支持数据库：Sqlite/Mysql

测试服务器：Tomcat9.0.4


![img](./img/demo2.png)

小组名称：伐木累
小组成员：王泽坤 李玉婷 吴振威


# To-do
 - [ ] 用户系统
 - [ ] 留言编辑修改删除
 - [ ] 点赞 评论系统
 
 
 # QA
 1. 数据库安装正确 密码账号无误的情况下出现数据库连接问题可能的解决方法：
 找了一下资料可能是客户端不支持新的密码加密方法 导致无法连连接
 ```mysql
use mysql;
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'new_password';
flush priviliges;
```


# Log
 2020.9。9 **启动项目**
