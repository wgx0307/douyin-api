# 抖音直播监控Api：弹幕、关注、送礼、点赞、来了 实时获取


## 抖音视频Api、抖音直播Api、抖音评论采集、抖音弹幕采集、抖音爬虫、抖音去水印、抖音视频下载、抖音视频解析
## 抖音直播数据、抖音数据采集、抖音直播监控

#### TiToData：专业的短视频数据采集、处理平台。
> 更多信息请联系微信：ifuxing123
```
海量数据采集
每天为客户采集5亿条数据
覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博

```



### 请求Api
```http
http://主机地址/douyin/liveroom/chat?token=xxx&room_id=6843198199583378191
```

### 

### 请求方式
```http
GET
```

### 

### 参数
| 字段 | 类型 | 说明 |
| --- | --- | --- |
| token | string | 接口授权码 |
| room_id | int | 直播间id |


### 

### 返回示例
```json
{
  "code": 200,
  "data": [
    {
      "type": "WebcastSocialMessage",
      "nickname": "薛莲",
      "uid": "111265487875",
      "short_id": "2072651305",
      "msg_id": "6843261579299965709",
      "sec_uid": "\"MS4wLjABAAAAmpM-hJ8AeUM8hSc3w5YlY8Q2ZUaiEu7uvt6cApLkyjg\"",
      "msg": "关注了主播"
    },
    {
      "type": "WebcastMemberMessage",
      "nickname": "用户5121651744892",
      "uid": "3654415794833197",
      "short_id": "2980367364",
      "msg_id": "6843261580051155719",
      "sec_uid": "\"MS4wLjABAAAAYcAoC-U8hSeyUxnGx_i5yoHRPPfwtr2wfplWg9KGsSMXyi7pWlPMV6XwMX7xpDgK\"",
      "msg": "来了"
    },
    {
      "type": "WebcastMemberMessage",
      "nickname": "大姑",
      "uid": "3091436132641739",
      "short_id": "2372670321",
      "msg_id": "6843261580789320462",
      "sec_uid": "\"MS4wLjABAAAAws0M9rKV7kK1ayWZ31Ebjsd8SwFI0rdf8goPY7HI8tELNK1XkFpX25yvHqe8WY9d\"",
      "msg": "来了"
    },
    {
      "type": "WebcastMemberMessage",
      "nickname": "我有一个好名字",
      "uid": "98675983627",
      "short_id": "1144452894",
      "msg_id": "6843261580508433159",
      "sec_uid": "\"MS4wLjABAAAAQhMqocOlzOLFvUE0tJKLQWKx1QuP8YXQmI2A6L3kWLQ\"",
      "msg": "来了"
    },
    {
      "type": "WebcastMemberMessage",
      "nickname": "李祥林",
      "uid": "2946292105354829",
      "short_id": "3496282621",
      "msg_id": "6843261585180560136",
      "sec_uid": "\"MS4wLjABAAAAcFKemBUvCP-CppApJZsS_4FEuIAWf2_2fpyrcsrs1PZi4U0PyXOK-3qRy4dVnAWW\"",
      "msg": "来了"
    },
 {
      "type": "WebcastChatMessage",
      "uid": "4006248980690445",
      "tid": "6843260054435826435",
      "nickname": "幸福",
      "text": "我不会买",
      "sec_uid": "MS4wLjABAAAAZWY-mQkfFitGRzNztj2FwNI6EJL6VJhEwuy3ehDmsVNBst1E2dU4umtJKmX4VW5S",
      "avatar": "https://p9-dy.byteimg.com/aweme/100x100/2dbd70006de205b08161b.jpeg?from=4010531038"
    },
    {
      "type": "WebcastMemberMessage",
      "nickname": "双子座一半天使，一半恶魔的陈欣彤🌺🌺",
      "uid": "945180703722141",
      "short_id": "2789104616",
      "msg_id": "6843261584941288205",
      "sec_uid": "\"MS4wLjABAAAAwvMatTP6mPsnysD0IPVmALci4CsfvRgOUi7lJxzq-c8\"",
      "msg": "来了"
    }
  ],
  "msg": 'success'
}
```
