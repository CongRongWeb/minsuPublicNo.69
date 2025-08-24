<p><h1 align="center">基于Java+Springboot+Vue的民宿管理系统</h1></p>

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>


## 一、系统介绍
本项目前后端分离

本系统分为管理员、商家、用户三种角色

用户角色包含以下功能：
- 注册、登录、民宿信息查看、房间信息(查看/预订/评论/收藏/退订/投诉)、在线客服、房间预订管理、房间退订管理、投诉反馈管理、我的收藏管理、个人中心、密码修改

商家角色包含以下功能：
- 包括用户的所有功能、个人民宿信息管理、房间管理、房间预订/退订审核、投诉反馈处理

管理员角色包含以下功能：
- 用户管理、商家管理、民宿信息管理、房间管理、房间类型管理、房间预订管理、房间退订管理、投诉反馈管理、我的收藏管理、轮播图管理、在线客服、个人中心、密码修改

## 二、所用技术

后端技术栈：

- Springboot
- MybatisPlus
- Mysql

前端技术栈：

- Vue 
- Vue-router 
- axios 
- element-ui

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上,Maven3.6, node14

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、前台页面
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
### 2、用户后台
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png).
### 3、商家后台
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
### 4、管理员后台
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)

## 五、浏览地址

前台访问地址：http://localhost:8080/springbootj470j/front/index.html
- 用户账号/密码：用户1/123456

后台访问地址：http://localhost:8081/
- 管理员账号/密码：abo/abo
- 供应商账号/密码：商家编号1/123456

## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件；
2. 使用IDEA/Eclipse导入项目，若为maven项目请选择maven，等待依赖下载完成；
3. 进入src/main/resources修改application.yml 里面的数据库配置
4. 启动项目后端项目
5. vscode或idea打开src/main/resources/admin/admin项目，
6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run serve,执行成功后会显示访问地址
