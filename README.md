# 电力管理系统 数据库课程设计



### 编程环境

- windows 10
- qt qt 5.14
- sqlserver
- odbc

### 题目要求

> 实现客户信息、用电类型（类别号、类别名、电价）及业务员管理；
> 实现客户用电信息管理（客户号、月份、用电类别号、用电度数）
> 实现客户费用管理（客户号、月份、费用、收费标志），收费标志的默认值为“未收”
> 实现收费登记（客户、月份、应收费用、实收费用、业务员），并编写触发器自动修改收费标志；
> 创建触发器，实现收费时自动更新应收费用和实收费用，计算本次结余，然后修改客户信息表中的结余余额；
> 创建存储过程统计指定月份应收费用和实收费用；
> 创建存储过程查询指定月份未交费的用户信息；

### 设计思路

见文档

### 部分界面



![image-20210209024127167](/document/image-20210209024127167.png)



这是一个小组作业，我主要负责界面交互部分，感谢@jx,wyy,zxy
