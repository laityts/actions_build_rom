<h1 align="center"> 利用Github Actions登录SSH编译ROM</h1>

---

<p align="center">
	A Github Action to build rom
</p>

<br />

## Actions secrets配置

| 名称               | 类型    | 描述                       |
| ------------------ | ------- | ------------------------------------------------------------|
| `CHATID`  | String  | TG频道CHATID  |
| `PASSWD`  | String  | sf服务器密码  |
| `RELEASE`  | String  | github的token值  |
| `SERVER_HOST`  | String  | 编译服务器地址  |
| `SERVER_PASSWORD`   | String  | 编译服务器密码  |
| `SERVER_USERNAME`  | String  | 编译服务器用户名  |
| `TELEGRAM_TOKEN`  | String  | tg机器人的token值  |

## 编译结果
可以在[Release](../../releases)下载