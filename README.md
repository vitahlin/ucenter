# Halo

Spring Boot 实现的一个用户中心，采用`JWT`进行身份验证，包含匿名用户注册登录、邮箱用户注册、邮箱用户登录等功能。


### 启动 

#### 依赖安装

采用`Gradle`管理。

#### `Mysql`和`Redis`启动

需要安装`docker`，首次需要编译所需镜像：
```
cd docker
make build
make up 
```

后续直接启动即可：
```
make start
```


