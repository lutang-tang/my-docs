# API 参考

这里是系统提供的示例 API 接口。

## 获取用户信息

**请求方法**：`GET`

**请求路径**：`/api/v1/user`

**返回示例**：
```json
{
  "status": "success",
  "data": {
    "id": 1001,
    "username": "lutang-tang",
    "role": "admin"
  }
}