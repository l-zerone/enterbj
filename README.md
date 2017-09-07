# enterbj

## 公告

**本应用为测试项目，请勿使用在线上**

## 应用介绍

辅助办理进京证，可以接入第三方API做到消息通知等

## 使用说明

目前SIGN处于测试中，还不对外开放

### 配置

config.ini

```ini
[test]
userId=ABCDEFGHIJKLMNOPQRSTUVWXYZ

[enterbj]
appkey=kkk
appsource=bjjj
```

### 运行

```bash
go run bin/main.go config.ini
```
或者
```bash
go build bin/main.go -o enterbj

./enterbj config.ini
```

## 版本记录

### 当前开发版本

完成基本接口的对接：

- [x] 获取用户信息
- [x] 获取车辆列表
- [x] 获取车辆环保信息
- [ ] 登录
- [ ] 验证码
- [ ] 获取其他驾驶人员列表
- [ ] 添加车辆
- [ ] 添加其他驾驶员
- [ ] 提交申请
