## 技术栈(Vue2.js + Node.js 全栈项目)

`Node.js` + `Koa2` + `Mysql`

## 开发环境

- Nodejs `v8.1.0`
- Koa `v2.3.0`
- Mysql `v5.7.0`

> 如果遇到报错，可能是因为不支持async await,请先升级node版本，

## 运行

> 只有超级管理员才可以删除文章，其他登录之后会自动注册，可以上传信息和修改信息

```
git clone https://github.com/wclimb/video-admin.git

cd video-admin

npm install  建议使用淘宝镜像(https://npm.taobao.org/) =>  cnpm i

npm i supervisor -g(安装过可以忽略)

npm run dev (运行项目)

npm test (测试)

ps: 需要先创建数据库，本项目的数据库名为 vuesql 不知道如何创建的可以看我另外一个项目Koa2-blog的README.md
```

## 后端管理后台功能

- [x] 注册
- [x] 登录
- [x] 登出
- [x] 上传video信息
- [x] 修改已上传的video信息
- [x] 查看喜欢/不喜欢的所有数据
- [x] 查看评论的所有数据
- [x] 查看评论的所有数据
- [x] 查看后台所有用户
- [x] 查看前端注册的所有用户

## 后端线上地址

技术栈：`node` + `koa2` + `mysql` 