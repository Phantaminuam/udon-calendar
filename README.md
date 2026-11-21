# udon-calendar

乌冬活动时间表 · iOS 日历订阅源

## 订阅地址

```
https://<你的用户名>.github.io/udon-calendar/udon.ics
```

## 说明

- 数据源：https://udonwiki.net/ （`/static/data/activity_hub.json`）
- 刷新规则：北京时间 **05:00** 切换游戏日，05:00 之前算前一天
- 每个限时活动 = 每周重复事件，开始前 **10 分钟**提醒
- 日常 9 项 = 每天 12:00 一条「清日常」提醒

## 更新

重新生成 `udon.ics` 后：

```bash
git add udon.ics && git commit -m "update" && git push
```

手机端会按系统策略自动拉取（最快约 15 分钟）。
