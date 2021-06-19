# Java产业扶贫系统-贫困村系统 poor-village

#### 介绍

  **SpringBoot2.X VUE2.6 Antd1.7.2  TkMyBatis Shiro1.5.0 Java1.8 管理系统 JVM 权限设计 可作为毕业设计和商业项目 产业扶贫系统** 

#### 联系作者

 **见文末** 

#### 演示地址
```
https://binfenyeke.com/admin-platform-health
账号: admin
密码: 123456
```
若演示地址不可用，可翻到文末扫码联系作者微信或者留言

#### 软件架构说明

#### 前端技术架构

1. Antd-VUE
2. 自定义权限指令
3. 自定义上传组件等

#### 后端技术架构

1. SpringBoot2.x
2. Shiro
3. Redis
4. MyBatis
5. MySQL
6. 分模块开发，自定义启动脚本，JVM调优
6. 多环境

#### 系统截图展示

1. 系统登陆注册
- 登陆界面
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195030_e7b55d70_1808544.png "系统登录.png")

- 用户注册
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195430_eb3486dd_1808544.png "用户注册.png")

2. 系统管理模块
- 系统主页
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195528_9bdfd4d9_1808544.png "系统首页.png")

- 菜单管理列表
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195602_a3a58831_1808544.png "菜单管理列表.png")

- 菜单新增与修改
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/200708_8e228692_1808544.png "菜单新增.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/200752_caa7905b_1808544.png "菜单修改.png")
- 角色管理
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195635_f3e544b9_1808544.png "角色管理.png")

- 角色管理新增与修改
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/200927_698cb5d6_1808544.png "角色新增.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/201014_193105b8_1808544.png "角色修改.png")

- 系统用户管理

![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195706_d1162fe3_1808544.png "系统用户管理.png")
3. 系统监控模块

- 请求日志
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/200527_5381f03e_1808544.png "请求日志.png")

- 系统监控-服务器
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195907_4eb47b59_1808544.png "系统监控-服务器信息.png")

- 系统监控-JVM
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/195923_8df54cd8_1808544.png "系统监控-JVM信息.png")

- 请求追踪
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/200542_1767baf8_1808544.png "请求追踪.png")


4. 贫困村信息

- 贫困村列表
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/193922_7d6cf131_1808544.png "贫困村列表.png")

- 贫困户信息
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/194018_86aa1fcc_1808544.png "贫困户信息.png")

- 贫困户管理
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/194109_4cc49ffc_1808544.png "贫困户列表.png")

- 扶贫产业信息
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/194208_93c62af9_1808544.png "扶贫产业信息.png")

- 数据导出
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/194455_43e4838d_1808544.png "数据导出.png")

- 数据导出展示
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/201149_507788a0_1808544.png "导出贫困村.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0523/201341_aba448f8_1808544.png "导出贫困村结果.png")

#### 项目代码展示

1. 前端VUE代码截图展示
![前端代码](https://images.gitee.com/uploads/images/2021/0523/194659_963d1066_1808544.png "前端代码.png")
2. 后端Java代码截图展示
![后端代码](https://images.gitee.com/uploads/images/2021/0523/194556_4e322db8_1808544.png "后端代码截图.png")


#### 系统功能模块概要
+ 系统登陆/注册
+ 系统主页
  - 系统主页折线图统计
    * 系统主页折线图统计
    + 系统模块导航
    - 系统在线数，访问数统计
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
	- 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
	- 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
	- 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
	- 系统字典新增
+ 系统监控
  - 在线用户管理
    * 在线用户条件查询
    + 在线用户踢出
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
	+ 系统访问IP分析
  - 系统请求追踪
    * 请求耗时追踪
    + 请求方法追踪
	+ 请求URL追踪
	+ 请响应状态追踪
  - 系统信息
    * JVM信息监控
    + 服务器信息监控
	+ 请求URL追踪
	+ 请响应状态追踪
+ 贫困村信息
  - 贫困村管理
    * 贫困村条件查询
    + 贫困村新增
	* 贫困村修改
    + 健康档案批量删除
    + 贫困村导出
+ 贫困户管理
  - 贫困户列表
    * 贫困户条件查询
    + 贫困户新增
	* 贫困户修改
    + 贫困户批量删除
    + 导出贫困户
+ 产业信息
  - 产业信息列表
    * 产业信息条件查询
    + 产业信息新增
	* 产业信息修改
    + 产业信息批量删除
    + 产业信息导出
#### 演示地址
```
https://binfenyeke.com/admin-platform-health
账号: admin
密码: 123456
```
若演示地址不可用或不匹配，可扫码联系作者微信或者留言

####  **联系作者** 

 **这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者。 17381852768 微信同号**  

![微信二维码-1](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E5%BE%AE%E4%BF%A1%E4%BA%8C%E7%BB%B4%E7%A0%81-1.png "微信二维码-1.png")

**这是作者的技术技术交流群二维码，如已过期请扫码联系作者拉群** 

![输入图片说明](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E6%8A%80%E6%9C%AF%E4%BA%A4%E6%B5%81%E7%BE%A4.png "技术交流群.png")

#### 安装教程

#### 后端安装方法
1.  mvn clean pakage
2.  tar -zxvf health-record-api.tar.gz (解压tar包)
3.  cd health-record-api
5.  sh /sbin/startup.sh dev

#### 前端安装方法
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
#### 使用说明

见上面安装方法

#### 参与贡献
1.  Fork 本仓库
2.  新建 Feature_xxx 分支
3.  提交代码
4.  新建 Pull Request

#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
