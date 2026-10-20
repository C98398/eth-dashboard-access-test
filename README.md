# ETH 三盘观察台

[打开看板](https://c98398.github.io/eth-dashboard-access-test/)

只读静态看板：原版模拟盘、反馈优化模拟盘以及从新起点开始记录的实盘。

- 展示经过字段白名单处理的真实数据快照；不包含 API 密钥、账户标识或原始数据库。
- 反馈盘继承的成交和迁移资金调整不计入策略收益。
- 实盘缺少完整平仓、费用或余额时显示待同步，不补历史、不用模拟数值代替。
- 数据时间采用北京时间。静态页面刷新不会直接查询交易所，最新数据以页面快照时间为准。

此仓库公开，页面展示的数据也公开。

浅色看板包含区间收益与回撤、每日净收益、分摊交易成本、ETH 15 分钟 K 线与真实开平仓标记，以及可筛选成交表。统计图使用 Apache ECharts 6.0.0，K 线使用 TradingView Lightweight Charts™ 5.2.1。两个图表库、真实快照与许可均随 HTML 发布，无外部 CDN 依赖。收益图支持 24 小时、7 天、30 天和全部历史；行情图支持 24/48 小时及全部历史。页面底部可查看完整开源许可。

TradingView Lightweight Charts™
Copyright (с) 2025 TradingView, Inc. https://www.tradingview.com/
