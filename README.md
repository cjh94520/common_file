# 记账鹿-币圈自动跟单平台

## **概述**

跟单交易是一种新型的社交投资方式，也是重要的投资组合管理工具。普通投资者可以复制交易达人的交易策略，并在市场中自动执行，轻松赚取超额收益；交易达人通过分享自己的交易策略，吸引跟随用户，获得相应利润分成。记账鹿旨在搭建高效透明且具有赚钱效应的跟单社区，为普通用户降低交易门槛，拓展盈利渠道。

自动跟单交易系统的优势：

*   无需制订您自己的交易策略，您只需选择一个投资高手（策略提供者），并根据他的交易指令进行自动跟单操作；
*   完全控制账户，包括可进行手动交易；
*   自动交易基于逻辑规则，可有效避免因不良情绪造成的交易干扰；

## 记账鹿自动交易记录

记账鹿平台自己的测试交易账号，会同步记账鹿自动跟单的所有交易记录到公开的第三方平台，欢迎大家查验。

币Coin：
![微信截图_20230507195031.png](https://upload-images.jianshu.io/upload_images/29045875-e0cfff36904ee2df.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)







## **平台特色**


### 适用范围

基于目前"人人都有一个微信"考虑，记账鹿基于**微信小程序**平台进行搭建。用户在使用上，无需额外的下载成本，打开微信搜索“记账鹿”小程序即可使用，方便快捷。

### 安全性

基于微信小程序搭建服务，用户相关的操作请求，均受到微信原生通信加密保护，用户无需担心相关信息在传输过程受到泄露。[安全鉴权模式介绍 | 微信开放文档](https://link.zhihu.com/?target=https%3A//developers.weixin.qq.com/miniprogram/dev/OpenApiDoc/getting_started/signature-verify.html%23%25E4%25BA%258C%25E3%2580%2581%2520%25E6%258E%25A5%25E5%258F%25A3%25E5%2586%2585%25E5%25AE%25B9%25E5%258A%25A0%25E5%25AF%2586%25E4%25BB%258B%25E7%25BB%258D)；同时，用户授权于记账鹿平台用于交易的权限，受非对称加密存储保护，后端服务器只能通过微信内部访问，隔绝外部服务攻击的可能，安全可靠。

### 交易策略来源

目前记账鹿提供交易达人的交易策略，交易达人来自各个知名的平台，其中包括OKX、火币、Bitget等平台。记账鹿会不断收集更多的平台和交易达人的数据，打造成一个聚合的数据平台。

### 为什么要使用记账鹿

1.  记账鹿基于微信小程序搭建，从微信->记账鹿小程序 ，使用体验上更舒适、便捷
2.  记账鹿数据采集于多个平台，能更有效协助用户发现交易达人，复制交易达人的交易策略盈利，提高了自身盈利的可能性
3.  部分平台本身也提供了跟单能力，但是受限于跟单人数限制、金额限制，用户无法在原有的平台跟单；可以选择记账鹿，数据来源跟原有平台一致。
4.  部分平台本身也提供了跟单能力，但是需要缴纳的跟单手续费用高；可以选择记账鹿，记账鹿**完全免费**，不会额外收取用户的费用，用户赚多少，全部都归到用户账户上。
5.  部分平台本身也提供了跟单能力，但是跟单人数太多，导致成交价跟交易达人的成交价差异大，结果可能出现交易达人盈利，但是自身出现亏损的情况。目前记账鹿在币安平台下单，采集非币安平台的交易达人数据，有效避免滑点的问题。

## 使用指南

### 入口

首先，在**微信**客户端，点击搜索栏，搜索"记账鹿"，点击小程序进入即可使用

![3_副本1.png](https://upload-images.jianshu.io/upload_images/29045875-8deb1bbe5415bcbd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



核心目前主要是跟单区
![a3.jpg](https://upload-images.jianshu.io/upload_images/29045875-41f82a244aa13fda.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

分别为跟单情况、API配置、策略配置

*   跟单情况：后续用户跟踪的所有订单都在这个页面显示，分别会有当前订单和历史订单
*   API配置：用户配置交易权限给记账鹿平台的地方，用户在页面中填写交易的API KEY和Secret给到平台，后续平台会用这个交易权限帮助用户自动跟单
*   策略配置：配置用户的交易策略。比如用户要跟随哪个交易达人，跟随的金额或者比例等等都在这里进行配置。

### 第一步

完成交易权限配置

目前用户自动交易的订单都在币安平台进行处理，所以需要用户切到币安交易平台申请API。下面是币安Android 的操作流程。
![a1.jpg](https://upload-images.jianshu.io/upload_images/29045875-8a662a96754690bf.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![a2.jpg](https://upload-images.jianshu.io/upload_images/29045875-9958146696b68c21.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![a3.jpg](https://upload-images.jianshu.io/upload_images/29045875-2d2a71310cdc155a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)





### 第二步

完成交易策略配置
![a1.jpg](https://upload-images.jianshu.io/upload_images/29045875-a3f4e09241b4c52e.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![a2.jpg](https://upload-images.jianshu.io/upload_images/29045875-c6d1bc84b4934039.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



### 第三步

等待订单到来

![a2.jpg](https://upload-images.jianshu.io/upload_images/29045875-2cde4b6e0eed972a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



## 关于我们

对小程序使用体验上有任何疑问，欢迎加入群聊跟我们细谈~

**QQ群**：点击链接加入群聊【【记账鹿】使用交流群】：[加入Q群](https://link.zhihu.com/?target=http%3A//qm.qq.com/cgi-bin/qm/qr%3F_wv%3D1027%26k%3DRlBinP6RH7w_wsKA1Cgt7-tDrywCE4_r%26authKey%3DrH62KB6eUWlXTpaBFOjEjC2DT8T2wm3JD65TkGdx6ymTPjThp%252FX63ymqTh9Guyoe%26noverify%3D0%26group_code%3D820157476)

**微博**：[记账鹿官方微博](https://weibo.com/u/7837879814)
* * *


记账鹿 是一款为交易者们搭建互助共赢、自由交流的平台，成为专业交易者和交易新人的桥梁。
在这里，交易者们可以体验自助跟单，共同打造新型交易社区。
