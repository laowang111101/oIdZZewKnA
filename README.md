# 教师工作量管理系统 java604

## 项目概述

教师工作量管理系统是基于Spring Boot和Vue.js的前后端分离项目。该项目适用于项目实训和在线课程任务等场景，旨在实现教师工作量管理的无纸化、系统化和规范化。

## 技术栈

- **前端**：Vue.js、HTML、CSS、JavaScript、ElementUI
- **后端**：Spring Boot、MyBatis Plus、MySQL
- **开发工具**：IDEA、VSCode
- **构建工具**：Maven、Node.js

## 环境说明

- JDK 1.8
- MySQL 8.0
- Maven 3.5
- Node.js 16.20

## 系统角色

系统分为以下两种角色：

- 管理员：负责教师管理、分类信息管理、课程信息管理、工作量管理和系统管理。
- 教师：负责个人中心管理、课程信息管理、工作量管理。

## 功能模块

### 个人中心模块

- 管理用户个人信息和权限设置。

### 教师管理模块（管理员）

- 实现对教师信息的增加、删除、修改和查询。

### 分类信息管理模块（管理员）

- 对课程分类等信息进行管理。

### 课程信息管理模块

- 管理员和教师均可管理课程相关信息。

### 工作量管理模块

- 管理员审核和统计教师工作量，教师提交和查询工作量。

### 系统管理模块（管理员）

- 进行系统设置、用户角色权限分配等操作。

## 系统核心亮点

- 基于B/S架构，便于部署和维护。
- 采用前后端分离的开发模式，提高开发效率。
- 实现了用户认证、数据管理和权限控制等关键模块，确保系统安全可靠。

## 目录结构

```
├── frontend  // 前端项目
│   ├── src
│   ├── public
│   ├── ...
├── backend  // 后端项目
│   ├── src
│   ├── pom.xml
│   ├── ...
└── database  // 数据库文件
    ├── sql
    └── ...
```

## 部署步骤

1. 准备环境：安装JDK 1.8、MySQL 8.0、Maven 3.5和Node.js 16.20。
2. 构建后端：在backend目录下执行`mvn package`命令。
3. 构建前端：在frontend目录下执行`npm run build`命令。
4. 部署应用：将构建后的后端jar包和前端dist目录部署到服务器。
5. 初始化数据库：导入database目录下的sql文件到MySQL数据库。
6. 启动应用：运行后端jar包，访问前端页面。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img14.360buyimg.com/ddimg/jfs/t1/334618/10/17133/11098/68d4f833Fb3152145/03a4363e0c3cda6e.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/328483/4/24168/14688/68d4f833Fbf5ff8c8/f7554a8066b9599d.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/328504/30/23951/15177/68d4f834F8b0fa2c6/009131c4cb67e718.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/332840/7/17149/35894/68d4f834F54dd7c6e/f941e75b5d9074bc.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/350974/7/7461/20143/68d4f834F18d7f4c7/782aec143a2ffe5d.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/346429/26/7238/8323/68d4f834F7e93dd49/4db58a547d5faf14.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/331798/13/17337/18492/68d4f835F837f18e2/c9227a75923e27a4.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/329869/14/17132/38474/68d4f835F7027a051/04101776db9f9528.jpg)

