# ginger

> 一个用来构建可扩展rest api的项目

实现了多客户端注册、认证。

是微服务和前后端分离的有效实践，随后，我会进行改写

## 实例

### 注册接口

url为   `http://127.0.0.1:5000/v1/client/register`

请求方式为  `post`

请求体为

```json

{"account":"1@qq.com", "secret":"johnson123456","type":100, "nickname":"johnson"}

```

### 返回结果


```json

{
    "error_code": 1000,
    "msg": {
        "account": [
            ""
        ]
    },
    "request": "POST /v1/client/register"
}

```
