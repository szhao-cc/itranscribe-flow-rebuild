# 增长审计 — iTranscribe

**在线查看：** https://szhao-cc.github.io/itranscribe-flow-rebuild/

五个思路，让 iTranscribe 现有的流量带来更多收入；另附一个可点击的原型，用 iTranscribe 自己的设计重做了引导流程和付费墙。由 Adapty 准备，2026 年 11 月。

| # | 思路 | 潜在效果 |
| :-- | :-- | :-- |
| 01 | 给关掉付费墙的用户多一个选择 | ARPU +10–15% |
| 02 | 在付费墙标题中点出用户的使用场景 | CR +15–20% |
| 03 | 在报价之前，把用户的回答复述给他们 | CR +10–15% |
| 04 | 把 4.6 分评分和媒体评价放到决策点旁边 | CR +10–15% |
| 05 | 默认选中年付，并在购买之后再显示“Activated” | ARPU +10–15% |

影响区间是 Adapty 基于订阅类应用的拆解与 A/B 测试得出的预期效果——并非 iTranscribe 的实测提升。每个价格、评分、引用和功能描述，都来自 iTranscribe 自己的 App Store 页面和应用内界面。

## 本地运行

```bash
python3 -m http.server 8000
```

然后打开 http://localhost:8000/。在地址后加 `?open=proto` 可直接进入原型。
