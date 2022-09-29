[AboutMe](https://maventalker.github.io/)

parking-base-serv，pom 项目，里面包含两个子模块：parking-admin，parking-gateway。
parking-admin，监控子项目的运行情况。
parking-gateway，网关子服务，配合 JWT 实现会话、验权等功用。
parking-carwash，洗车子服务，连接 park-carwash 数据库。
parking-card，积分子服务，连接 park-card 数据库。
parking-charging，计费子服务，连接 parking-charging 存储库
parking-finance，财务子服务，连接 parking-finance 存储库。
parking-member，会员子服务，连接 park-member 存储库。
parking-resource，资源子服务，连接 park-resource 存储库。
parking-message，消息子服务，连接 park-message 存储库，连同 rocketmq 存储消息数据
parking-common，存储通用的工具类，实体包等等。
