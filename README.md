# polymarket_btc_15m_agent
AI 驱动的 Polymarket BTC 15 分钟涨跌自动交易代理，支持模拟与真实交易、风险控制、自动结算和实时数据面板。

## 发布可执行文件到 GitHub Releases

1. 将需要发布的可执行文件放到仓库根目录的 `releases/` 文件夹中。
2. 在 GitHub Actions 中手动运行 `Publish executables to release` 工作流，填写目标 `tag`（例如 `v0.1.0`）。
3. 工作流会自动把 `releases/` 下的文件上传到对应的 GitHub Release 资产中。
