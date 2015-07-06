基于Java的技术栈学习
==============

##考察点
* Spring + hibernate的配置和环境搭建
* Spring REST API的编写
* Ajax应用，angular框架，Bootstrap使用
* 数据库迁移的概念
* ...


## 需求

- 将给定的程序上跑通，能在命令行顺利的看到"Hello World"(包括基本的测试框架、文件结构、gradle)
- 实现用户管理系统

### 第一阶段

1. 将网站跑起来
2. 使用JSP在页面上显示出用户的基本信息（静态信息），包括姓名、性别、邮箱、年龄

### 第二阶段

使用MySQL来记录用户的信息，并使用hibernate作为ORM工具

### 第三阶段

完成用户信息的增删改查

### 第四阶段

引入Spring

### 第五阶段

1. 在JSP版本的实现上，写一个登录页面，实现登录功能
2. 现行的JSP实现和基础数据是没有在创建和修改用户时对密码进行md5码加密的，要求自己加上。
3. 把JSP版本下的所有用户管理界面的URL，都管理起来，不能录不能访问，直接跳回登录页面。
4. 如果访问了某不登录无法访问的页面A，就跳回登录页。登录成功就可以跳回页面A，要求用cookie实现。（登录了两次也能跳回，一旦登录了，cookie的内容应该被清空）
5. 此时应该有git了

### 第五阶段

1. 这是一个健身房管理系统。系统里有雇员（Employee）, 顾客（Customer）, 课程（Course）, Employee有三种：OPs，HR，COACH（教练）。
2. 一个顾客可以上多门课，每门课有一个教练。每门课要有课程的时间安排，一门课一定是跨很多天的（精确到天就可以了）。
3. 每个雇员要关联一个User，1对1的关系
4. 一个顾客可以指定一个私人教练，且只能指定一个，私人教练可以跟他越私人课程，时间是现约现安排，但是教练有课程的日子不能约私人课程
5. 所有的设置，都参考User的增删改查。只要能增删改查就好了，理解为有一个人操作一台电脑处理所有的企业运转数据。
6. 显示课程表

