# spirngcloud

使用了springboot spring-data-jpa redis elasticsearch（2.4.6） vue.js 

zsk-app  消费者，端口 8021

zsk-commons 公共包

zsk-dao  数据包

zsk-ddo  jpa实体

zsk-dvo  消费端实体

zsk-eureka  注册中心  端口8001

zsk-service  服务端   端口8011

需要启动3个服务

启动顺序zsk-eureka -> zsk-service -> zsk-app


启动方式
1、可以直接用eclipse启动，开发环境
2、打成jar包，java -jar  xxx.jar 命令启动

