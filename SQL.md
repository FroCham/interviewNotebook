一、基础
二、创建表
三、修改表
四、插入
五、更新
六、删除
七、查询
八、排序
九、过滤
十、通配符
十一、计算字段
十二、函数
十三、分组
十四、子查询
十五、连接
十六、组合查询
十七、视图
十八、存储过程
十九、游标
二十、触发器
二十一、事务管理
二十二、字符集
二十三、权限管理
参考资料

一、基础
模式定义了数据如何存储、存储什么样的数据以及数据如何分解等信息，数据库和表都有模式
SQL（Structured Query Language）
SQL语句不区分大小写

SQL支持以下三种注释
#注释
FROM mytable; --注释
/* 注释1
   注释2 */

数据库创建与使用
CREATE DATABASE test
USE test

二、创建表
CREATE TABLE mytable(
  id INT NOT NULL AUTO_INCREMENT,
  col1 INT NOT NULL DEFAULT 1,


















