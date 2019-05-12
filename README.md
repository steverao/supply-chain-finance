﻿# KA供应链金融平台（Supply Chain Finance）

## 1 项目简介

#### 1.1 系统介绍

由于赊账已经成为企业之间交易过程中的常态，而大型企业下的链属企业由于规模小，资金链紧张，赊账对其后续的生产经营影响极大。所以本着为企业提供资金服务保障企业生产经营的目的该供应链金融平台应运而生。该系统两大核心用户为出资方（银行或保理商）和企业（核心企业或链属企业）。通过出资方为企业提供的两大核心业务——债转和保理，为企业解决资金链紧张难题。

#### 1.2 业务介绍

##### 1.2.1 保理服务

简单来说就是卖方将货物卖给买方，卖方将贸易过程中销售或合同所产生的应收账款转让给保理商，再由保理商为卖方提供现金流提前用于采购、生产等，以避免应收账款产生到收回期间企业资金周转的难题。最后，保理商从中收取服务费的一种金融服务。详细说明如下图：

![](document-illustration/bl.bmp)

##### 1.2.2 债转服务	

#### 1.2 技术清单

- **后端:** `spring`+`springMVC`+`Mybatis`等

- **数据库:** `mysql`

- 分布式中间件：`Redis`、`JSF（京东自研的RPC框架）`和`ZooKeeper`

#### 1.3 我的任务

-  我主要参与系统中的最底层公共服务模块相关开发。
-  梳理系统原型图，完成用户管理，企业管理和企业实名认证相关十多个功能点的接口定义。
-  完成用户管理，企业管理和企业实名认证等在内的十多个功能点的`Http`接口功能开发，另外完成了合同签章和短信验证码两个功能点的`JSP`接口功能开发。
