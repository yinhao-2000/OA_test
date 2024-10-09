# 云上办公系统
## 项目描述
一套功能完整基于SpringBoot的自动办公系统。系统主要包含管理端和员工端。管理端拥有权限管理、审批管理、公众号菜单管理功能。员工端采用微信公众号操作，拥有审批申请、微信授权登录、消息推送等功能。
## 技术栈
SpringBoot+MyBatisPlus+SpringSecurity+Redis+Activiti+MySQL
## 具体实现
通过MyBatisPlus来操作MySQL数据库，实现增删改查等操作来管理用户数据。  
在用户认证过程中，使用Redis作为本地缓存，使用SpringSecurity来实现用户认证流程，提高认证授权的安全性和性能。  
使用Activiti实现工作审批流程的自行管理，减少业务系统由于流程变更进行系统升级改造的工作量，从而提高系统的健壮性。
## 个人收获
熟悉使用SpringBoot框架下开发项目的操作流程。熟悉了Redis作为数据缓存的实际使用场景及优势。  
了解SpringSecurity和Activiti的具体执行流程和简单部署，了解其在项目中的使用优势。
