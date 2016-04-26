本项目是基于dubbo的分布式部署项目

环境配置

    zookeeper：用于dubbo注册服务
    dubbo管理控制台：用于查看dubbo所提供的接口



启动项目前需要修改以下文件：

    数据库配置文件：jdbc.properties
    dubbo服务地址：service.properties

    先启动edu-service-user项目，这是接口的提供者

    然后启动edu-web-boss项目，这是接口的消费者



前台页面默认admin登陆密码是123456
