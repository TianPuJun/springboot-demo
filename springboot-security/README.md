springboot集成security
mysql数据库springboot-security
https://docs.spring.io/spring-security-kerberos/docs/1.0.1.RELEASE/reference/htmlsingle/
[官网demo](https://spring.io/guides/gs/securing-web/)
# 第一版 复制官网demo完成
用户名 user
密码 password
点击 http://127.0.0.1:8080 进入首页

* 配置方法权限验证时需要配置方法验证开启,不然方法权限无法生效

```text
@EnableGlobalMethodSecurity(prePostEnabled = true)

```
