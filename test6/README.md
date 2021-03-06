# 实验6：基于GitHub的实验管理平台的分析与设计
|学号|班级|姓名|照片|
|:-------:|:-------------: | :----------:|:---:|
|201510414108|软件(本)15-1|郭昆进|![flow1](../head.jpg)|

## 1. 概述
- 基于GitHub的实验管理平台的作用是在线管理实验成绩的Web应用系统。学生和老师的实验内容均存放在GitHUB
页面上。
- 学生的功能主要有：一是设置自己的GitHub用户名，二是查询自己的实验成绩。学生的GitHub用户名是公开的，但成绩不公开。
- 老师的功能主要有：一是批改每个学生的成绩，二是查看每个学生的成绩。
- 老师和学生都能通过本系统的链接方便地跳转到学生的每个GitHUB实验目录，以便批改实验或者查看实验情况。
- 实验成绩按数字分数计算，每项实验的满分为100分，最低为0分。
- 系统自动计算每个学生的所有实验的平均分。

## 2. 系统总体结构
![flow1](./img/sys.png)

[界面设计](https://guokunjin.github.io/is_analysis/test6/ui/login_html.html)

## 3. 用例图设计 [源码](./src/usecase.puml)
![](./img/usecase.png)

## 4. 类图设计 [源码](./src/class.puml)
![](./img/class.png)

## 5. 数据库设计
- ### [参见数据库设计](./数据库设计.md)

## 6. 用例及界面详细设计

- ### [“登录”用例](./用例/登录.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/login_html.html)
- ### [“登出”用例](./用例/登出.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“查看用户信息”用例](./用例/查看用户信息.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“修改用户信息”用例](./用例/修改用户信息.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“修改密码”用例](./用例/修改密码.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“录入班级信息”用例](./用例/录入班级信息.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入课程信息”用例](./用例/录入课程信息.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入学生信息”用例](./用例/录入学生信息.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入教师信息”用例](./用例/录入教师信息.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入院系信息”用例](./用例/录入院系信息.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“学生所修课程导入”用例](./用例/学生所修课程导入.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“教师所授课程导入”用例](./用例/教师所授课程导入.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“发布实验”用例](./用例/发布实验.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/publishtest_html.html)
- ### [“成绩录入”用例](./用例/成绩录入.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/correct_html.html)
- ### [“打印成绩”用例](./用例/打印成绩.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-teacher_html.html)
- ### [“选择学期”用例](./用例/选择学期.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-teacher_html.html)
- ### [“学生列表”用例](./用例/学生列表.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-teacher_html.html)
- ### [“课程列表”用例](./用例/课程列表.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“查看成绩”用例](./用例/查看成绩.md),[界面](https://guokunjin.github.io/is_analysis/test6/ui/index-student_html.html)


