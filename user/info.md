# 个人信息

> 获取个人信息  
> `/api/user/info` `GET` `需要cookies`

## 返回内容

|     key     |        value         |  type  |
| :---------: | :------------------: | :----: |
|    code     |      请求状态码      |  int   |
|     msg     |     请求状态信息     | string |
| description | 更详细的请求状态信息 | string |
|    data     |       真实数据       |  JSON  |

### data
|     key     |     value      | type  |
| :---------: | :------------: | :---: |
|  userInfo   |    用户信息    | JSON  |
| serviceTime | 返回时的时间戳 |  int  |

#### userInfo

|     key     |             value              |  type  |
| :---------: | :----------------------------: | :----: |
|     age     |              年龄              |  int   |
|   avatar    |            头像URL             | string |
|    gold     |            剩余金币            |  int   |
|     id      |           训练师编号           |  int   |
|  nickname   |            用户昵称            | string |
|     sex     |     性别（m 为男，s 为女）     | string |
|  username   |             用户名             | string |
|  telephone  |            电话号码            | string |
| description |            个性签名            | string |
|    doing    |           正在做的事           | string |
|    level    |              等级              |  int   |
|     qq      |              QQ号              | string |
|    email    |              邮箱              | string |
|  realname   | 真名（1 为潜力新星，以此类推） | string |

