# wechat-im
### 微信小程序即时通讯组件
#### 集成方式 请看 http://blog.csdn.net/sinat_27612147/article/details/78456363

更新日志：

2018-06-29
 - 加入`wx.getRecorderManager()`以支持小程序基础库1.6.0以上。
 - 兼容长按事件，根据版本调用`longpress`或`longtap`。
 - 新增接口`voiceType: 'mp3'`,有效值为 aac/mp3 ,默认值为'mp3'

2018-06-26
 - 新增右下角加号button点击事件
```
chatInput.setExtraButtonClickListener(function (dismiss) {
            console.log('Extra弹窗是否消息', dismiss);
        })
```
