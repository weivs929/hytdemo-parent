# hytdemo-parent
idea创建多module子项目


```
├── hyt-parent
│   ├── hyt-tmall-api  # 会员注册绑定查询SPI接口&TMC消息接收 
│   ├── hyt-jst-job    # 获取天猫聚石塔订单等数据
│   ├── hyt-crm-api    # 定义API,供CRM调用
│   ├── hyt-tmall-web  # PC/手机端的会员中心页面模块
│   ├── hyt-admin-web  # 后台管理模块
│   ├── hyt-biz        # 基础包，存放共用的东西；如定义SPI，供CRM实现。

```



## 项目使用技术
* jdk 1.8(熟悉下新语法，对开发效率有帮助)
* jetty9 or tomcat9
* spring mvc
* mybatis
* cat监控
* lombok
* dozer
* guava
* mysql
* 微信通知 
