# Risk API

### 全局字段说明

userId：为业务系统向风控系统传输时，用来标示唯一用户。

submitTime：为业务系统向风控系统提交风控数据时的时间。

### 补充说明

1. 运营商认证，尽可能使用魔蝎数据定义的接口与参数。
2. 风控报告字段，待接好三方数据源及风控策略集后，根据情况再产出对应的接口文档。

### BaseURL

[https://apifktest.yfbigdata.com/](https://apifktest.yfbigdata.com/)

### 版本更新说明

| 版本号 | 修改时间 | 修改人 | 修改内容 |
| :--- | :--- | :--- | :--- |
| 1.0.0 | 2018-12-27 17:23:03 | 刘少寒 | 创建风控接口 |
| 1.0.0.1 | 2019-01-04 18:02:11 | 刘少寒 | 新增验证身份证和姓名是否匹配的URL |
| 1.0.0.2 | 2019-01-07 10:25:13 | 刘少寒 | 订单提交，新增同盾需要的字段。 |
| 1.0.0.3 | 2019-01-07 14:41:57 | 刘少寒 | 新增几个接口的URL |
| 1.0.1 | 2019-01-07 17:16:15 | 刘少寒 | 新增贷后2个接口：逾期订单推送/逾期订单状态更新 |
| 1.0.2 | 2019-01-08 15:52:12 | 严浩 | 1）新增获取风控报告接口；2）修改自动风控结果回调/查询的风控命中项的字段 |

# 目录

* [Readme](/README.md)

* [黑名单库拉取](/黑名单库拉取.md)

* [黑名单验证](/黑名单验证.md)

* [验证身份和姓名是否匹配](/验证身份证号和姓名是否匹配.md)

* [身份证照片和活体照片相似度](/身份证照片和活体截图照片相似度.md)

* [验证活体照片与公安照片相似度](/验证活体截图照片与公安照片相似度.md)

* [紧急联系人提交](/紧急联系人提交.md)

* [通讯录和通话记录上传](/通讯录和通话记录上传.md)

* [运营商认证](/运营商认证.md)

* [订单提交](/订单提交.md)

* [自动风控结果回调](//自动风控结果回调.md)

* [自动风控结果查询](/自动风控结果查询.md)

* [获取风控报告の检查项](/获取风控报告の检查项.md)

* [贷后:逾期订单推送](/贷后:逾期订单推送.md)

* [贷后:逾期订单状态更新](/贷后:逾期订单状态更新.md)



