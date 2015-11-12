# androidfancier.cn社区代码，基于[gopher](https://github.com/jimmykuu/gopher)


配置文件  *etc/config.json* 

- superusers: 内容为用户名,如果没有管理员,内容为"",如果有多个,用英文逗号隔开
- analytics_file: 内容为统计分析代码的文件名
- time_zone_offset: 时差，跟UTC的时间差，单位小时
- github_login_redirect: 第三方登录失败无法获取cookie跳转地址
- github_login_success_redirect: 第三放登录成功后跳转地址
- cookie_secure: 第三方登录需要使用HTTPS，当设置为false供本地测试使用
- deferpanic_api_key: deferpanic.com的Api Key，用于监控panic
- gt_captcha_id: geetest.com 服务的 id
- gt_private_key: geetest.com 服务的 key


需要先启动MongoDB

然后运行
$ $GOPATH/bin/server



