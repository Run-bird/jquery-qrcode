## Enhancer三方组件 jquery-qrcode 使用说明
### 查看Demo 【账号】test 【密码】123456
### 简介 [Demo](http://47.96.99.14:5301/#115)
- jquery-qrcode是基于[Enhancer](https://enhancer.io)平台开发的组件, 能在此平台上良好运行。
- jquery-qrcode可将 数据 , Html 和 Excel 任意转换。

### 生成界面
![](https://github.com/Run-bird/jquery-qrcode/blob/master/images/WechatIMG1.jpeg)
### 配置界面
![](https://github.com/Run-bird/jquery-qrcode/blob/master/images/WechatIMG2.jpeg)

### 使用说明
- 在[Enhancer](https://enhancer.io)上注册，新建项目使用此组件。
- 在图二界面设置组件的数据源，及相关配置。

### 数据源设置
- 数据源格式说明：必须是对象数组，如 2 所示。
```
"https://enhancer.io"            【格式一】字符串

[{
  "text": "https://enhancer.io"  【格式二】包含text属性的对象数组
}]
```

### 组件功能
- 讲文本转化成二维码


### 可用事件说明
#### 单击二维码（On Qrcode Click）
- 【事件 ID】onQrcodeClick
- 【触发时机】单击生成的二维码时。

### 可用变量说明 [Demo](http://47.96.99.14:5301/#114)
#### QRCODE_CONTENT
- 【类型】string
- 【说明】二维码文本内容
- 【示例】'https://enahncer.io'

### 其它
- [Enhancer 教程](https://enhancer.io/tutorials)
- [Enhancer 社区](https://forum.enhancer.io/#p=1&t=5)