# MYSQL
梳理数据库基础知识，以及mysql使用过程中的笔记、总结。



## 数据库概述及mysql结构

### 表之间三种关系

https://blog.csdn.net/lengjinghk/article/details/52140276



## [数据库安装](./mysql-install.md)



## sql语法

https://www.runoob.com/sql/sql-tutorial.html

 

多表查询应避免出现笛卡尔积

 

-- 出现笛卡尔积的写法

select * from tablea ,tableb where tablea.id=tableb.id sql

-- 不出现的写法

select * from tablea join tableb on tablea.id=tableb.id

分库分表



## 数据库连接池原理

https://blog.csdn.net/guobinhui/article/details/85157805

 

## mysql 数据库监控

https://blog.csdn.net/u013421629/article/details/78741525



## 数据分片处理

背景：批量程序分片设置为64片时，数据库服务器CPU占用为100%。



