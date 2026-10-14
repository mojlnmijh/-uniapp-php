# 教育培训系统uniapp+php
获取源码：ym7k.com/11811/
教育培训系统采用 UniApp + PHP 技术栈，是一套兼顾多端发布与快速开发的实用方案。UniApp 负责前端，一套代码可编译到微信小程序、H5、APP 及支付宝等平台；PHP 负责后端，通常搭配 ThinkPHP 6/8 或 Laravel，提供 API 接口与管理后台。

核心模块包括：课程管理（图文/音频/视频/直播）、学员管理、订单支付、会员体系、分销与优惠券、讲师入驻、学习进度、考试题库、数据统计。管理后台多基于 FastAdmin 或 Vue + Element 搭建，支持 RBAC 权限、多角色协作。

技术要点：前端用条件编译处理各端支付、登录、分享差异；后端用 JWT 鉴权、Redis 缓存、队列削峰；视频需对接 OSS + CDN 防盗链；直播可接第三方推拉流服务。

常见坑：号称全开源但核心文件加密；抖音/支付宝端支付登录未真跑通；视频播放域名未配置；分销层级超三级涉传；虚拟商品退款规则不清。

合规红线：ICP 备案 + 经营性 ICP 许可证、网络文化经营许可证（音视频/直播）、出版物经营许可证（电子书）、个人信息保护、版权授权、发票税务。
<img width="1900" height="918" alt="202504231051124" src="https://github.com/user-attachments/assets/148e7173-ddf1-4dd5-8128-e6951f7c57d5" />
<img width="1254" height="906" alt="2025042310510571" src="https://github.com/user-attachments/assets/54da13a0-00cc-481c-9eb7-12939dc58cad" />

