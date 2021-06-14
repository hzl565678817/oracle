﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 实验6（期末考核） 基于Oracle的```某项目```数据库设计 | [返回](./README.md)

- 期末考核要求

  - 自行设计一个信息系统的数据库项目，自拟```某项目```名称。
  - 设计项目涉及的表及表空间使用方案。至少5张表和5万条数据，两个表空间。
  - 设计权限及用户分配方案。至少两类角色，两个用户。
  - 在数据库中建立一个程序包，在包中用PL/SQL语言设计一些存储过程和函数，实现比较复杂的业务逻辑，用模拟数据进行执行计划分析。
  - 设计自动备份方案或则手工备份方案。
  - 设计容灾方案。使用两台主机，通过DataGuard实现数据库整体的异地备份(可选)。

## 实验注意事项，完成时间： 2021-6-15日前上交

- 实验在自己的计算机上完成。
- 文档`必须提交`到你的Oracle项目中的test6目录中。文档必须上传两套，因此你的test6目录中必须至少有两个文件：
  - 一个是Markdown格式的，文件名称是test6.md。
  - 另一个是Word格式的，文件名称是test6_design.docx。参见[test6_design.docx](./test6_design.docx)，文件不用打印。
- 上交后，通过这个地址应该可以打开你的源码：https://github.com/你的用户名/oracle/tree/master/test6
- 文档中所有设计和数据都必须是你自己独立完成的真实实验结果。不得抄袭，杜撰。

## 评分标准

| 评分项|评分标准|满分|
|:-----|:-----|:-----|
|文档整体|文档内容详实、规范，美观大方|10|
|表设计|表，表空间设计合理，数据合理|20|
|用户管理|权限及用户分配方案设计正确|20|
|PL/SQL设计|存储过程和函数设计正确|30|
|备份方案|备份方案设计正确|20|