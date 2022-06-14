# 基于Bark的自动化推送

* 仅适用iOS
* iOS中 `快捷指令 - 自动化任务` 可以实现相同功能(但是不可以给自动化任务取名, 遂放弃)

## 自动化任务列表

- 跳转云闪付 - 浙里好券 
```
https://api.day.app/xxxxx/优惠券提醒/浙里好券?url=upwallet%3A%2F%2Fapplet%3FtoLink%3Dhttps%253A%252F%252Fzjyhjy.95516.com%252Fzlhq%252F%26encryptAppId%3D9fb3c78a9077c2e8&level=timeSensitive
```

- 掌上生活
```
https://api.day.app/xxxxx/优惠券提醒/周三半价?url=cmblife:&level=timeSensitive
```

### 致谢
[Finb / Bark](https://github.com/Finb/Bark)

[支付宝、云闪付小程序一键直达：URL Scheme 跳转扩展用法](https://sspai.com/post/68497)

[URL Scheme 查询指南](https://sspai.com/post/66334)
