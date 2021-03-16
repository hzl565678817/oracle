# oracle
##实验一
#####姓名：何政梁 
#####学号：201810414112 
#####班级：18软工一班

##实验目的
分析SQL执行计划，执行SQL语句的优化指导。理解分析SQL语句的执行计划的重要作用。
##实验内容
1、对Oracle12c中的HR人力资源管理系统中的表进行查询与分析。
2、首先运行和分析教材中的样例：本训练任务目的是查询两个部门('IT'和'Sales')的部门总人数和平均工资，以下两个查询的结果是一样的。但效率不相同。
3、设计自己的查询语句，并作相应的分析，查询语句不能太简单。

####* 查询1
```
SELECT d.department_name,count(e.job_id)as "部门总人数",
avg(e.salary)as "平均工资"
from hr.departments d,hr.employees e
where d.department_id = e.department_id
and d.department_name in ('IT','Sales')
GROUP BY d.department_name;
```
####* 查询1结果
![](1.jpg)
####* 查询1分析
