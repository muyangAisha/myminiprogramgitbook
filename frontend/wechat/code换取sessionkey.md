# code换取sessionKey

#### **接口基本信息**

* **接口描述**

  小程序前端将code给后端生成秘钥sessionKey

* **请求方式**

  GET

* **URL**

  /wx/c2s?code=xxxxxxxxxxxxxxxxxx

* **接口使用权限校验**

  不需登录

#### **请求参数**

| 名称 | 类型 | 必选 | 说明 |
| --- | --- | --- | --- |
| code | String | Yes | 微信登录凭证（code） |

#### **响应参数**

| 名称 | 类型  | 说明 |
| --- | --- |  --- |
| tempSession | String | 临时Session |

#### **请求数据样例**

```url
/wx/c2s?code=011DdH7d1rN2wz0d5a8d1SqU7d1DdH7q
```

#### **响应数据样例**

```json
{
	"code": 0,
	"data": {
		"tempSession": "2Y5DROxsh3OmeAgluEpZFQ=="
	},
	"message": "请求成功",
	"timestamp": "20190903110848"
}
```



