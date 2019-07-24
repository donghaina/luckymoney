# Spring Boot项目尝鲜

## 如何创建项目
- 使用IDEA创建
- 使用start.spring.io 创建


## 如何启动项目
- 使用 IDEA 直接 run 启动入口Java文件
- 使用 maven 启动
    - 进入项目根目录
    - 执行 mvn spring-boot:run
- 构建之后执行 jar 包【一般在生产环境使用】
    - 进入项目根目录
    - mvn clean package
    - java -jar target/luckymoney-0.0.1-SNAPSHOT.jar  