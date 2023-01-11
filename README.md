# <font size="6p">spring-oauth2-sample</font> <font size="5p">  | [English Documentation](README_EN.md)</font>

<p align="left">
	<a href="https://github.com/ReLive27/spring-security-oauth2-sample/stargazers"><img src="https://img.shields.io/github/stars/ReLive27/spring-security-oauth2-sample?style=flat-square&logo=GitHub"></a>
	<a href="https://github.com/ReLive27/spring-security-oauth2-sample/network/members"><img src="https://img.shields.io/github/forks/ReLive27/spring-security-oauth2-sample?style=flat-square&logo=GitHub"></a>
	<a href="https://github.com/ReLive27/spring-security-oauth2-sample/watchers"><img src="https://img.shields.io/github/watchers/ReLive27/spring-security-oauth2-sample?style=flat-square&logo=GitHub"></a>
	<a href="https://github.com/ReLive27/spring-security-oauth2-sample/issues"><img src="https://img.shields.io/github/issues/ReLive27/spring-security-oauth2-sample.svg?style=flat-square&logo=GitHub"></a>
	<a href="https://github.com/ReLive27/spring-security-oauth2-sample/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ReLive27/spring-security-oauth2-sample.svg?style=flat-square"></a>
</p>

这个项目是一个 [Spring Authorization Server](https://spring.io/projects/spring-authorization-server) 示例教程的集合。它建立在 Spring
Security 5 之上， 这里的模块涵盖了 Spring Authorization Server 的许多其他方面。

## 相关文章:

- [将JWT与Spring Security OAuth2结合使用](https://relive27.github.io/blog/spring-security-oauth2-jwt)
- [自定义OAuth2授权同意页面](https://relive27.github.io/blog/custom-oauth2-consent-page)
- [Spring Security 持久化OAuth2客户端](https://relive27.github.io/blog/persisrence-oauth2-client)
- [Spring Security OAuth2客户端凭据授权](https://relive27.github.io/blog/oauth2-client-model)
- [Spring Security OAuth2 带有用于代码交换的证明密钥 (PKCE) 的授权码流](https://relive27.github.io/blog/oauth2-pkce)
- [Spring Security OAuth2登录](https://relive27.github.io/blog/oauth2-login)
- [Spring Security和OpenID Connect](https://relive27.github.io/blog/springn-security-oidc)
- [将Spring Cloud Gateway 与OAuth2模式一起使用](https://relive27.github.io/blog/spring-gateway-oauth2)
- [Spring Security OAuth2实现简单的密钥轮换及配置资源服务器JWK缓存](https://relive27.github.io/blog/jwk-cache-and-rotate-key)
- [将Spring Security OAuth2授权服务JWK与Consul 配置中心结合使用](https://relive27.github.io/blog/oauth2-jwk-consul-config)
- [Spring Security OAuth2 Opaque 令牌的简单使用指南](https://relive27.github.io/blog/oauth2-opaque-token)
- [Spring Security OAuth2 内省协议与 JWT 结合使用指南](https://relive27.github.io/blog/oauth2-introspection-with-jwt)
- [Spring Security OAuth 2.0授权服务器结合Redis实现获取accessToken速率限制](https://relive27.github.io/blog/oauth2-token-access-restrictions)
- [(待更新) 单页应用程序（SPA）的 OAuth2.0 安全实践]()
- ...

  [comment]: <> (- [（待更新）Spring Security OAuth2和动态客户端注册]&#40;&#41;)

  [comment]: <> (- [（待更新）Spring Security 实现OAuth2.0协议核心接口指南]&#40;&#41;)

## Spring 框架版本

| Spring Boot 版本  | Spring Cloud 版本  | Spring Authorization Server 版本 | Spring Security 版本  |
| ---------------- | ----------------- |----------------- | --------- | 
| 2.6.7            | 2021.0.2          | 0.3.1            |    5.6.3       |

## 构建项目

spring-oauth2-sample 使用基于 [Maven](https://maven.apache.org/) 的构建系统。

### 先决条件

[Git](https://help.github.com/set-up-git-redirect) 和 [JDK8](https://www.oracle.com/technetwork/java/javase/downloads)
构建。

确保您的`JAVA_HOME`环境变量指向 `jdk1.8.0` 从 JDK 下载中提取的文件夹。

### 检查来源

```
git clone git@github.com:ReLive27/spring-security-oauth2-sample.git
```

### 构建并安装项目：

```
./mvn clean install -Dmaven.test.skip=true
```

## 贡献

非常欢迎[提出请求](https://help.github.com/articles/creating-a-pull-request) 。

## 许可

spring-oauth2-sample 是在 [Apache 2.0 许可](https://www.apache.org/licenses/LICENSE-2.0.html) 下发布的开源软件 。
