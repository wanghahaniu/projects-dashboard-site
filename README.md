# 我的网站看板

个人网站与智能分析工具的统一入口。

## 已收录网站

- [黑天鹅分析引擎](https://wanghahaniu.github.io/blackswan/) · [查看源码](https://github.com/wanghahaniu/blackswan)
- [事实核查引擎](https://wanghahaniu.github.io/factcheck/) · [查看源码](https://github.com/wanghahaniu/factcheck)
- [K线行情智能归因与宏观推演系统](https://wanghahaniu.github.io/kline-attribution-site/) · [查看源码](https://github.com/wanghahaniu/kline-attribution-site)
- [DeepSeek Harness](http://127.0.0.1:3080/) · 本地服务，无公开源码入口
- [橙子API](https://open.hitick.top/) · 在线 API 服务
- [美伊局势日报](https://wanghahaniu.github.io/us-iran-daily/) · 每日局势简报
- [期货信号看板](http://110.42.220.207:8000/#bu2610) · 期货行情与交易信号

## 本地预览

```bash
python -m http.server 8000
```

然后打开 <http://localhost:8000/>。

## GitHub Pages 部署

本项目为纯静态单页，无需构建步骤。将 `main` 分支根目录作为 GitHub Pages 来源，入口文件为 `index.html`。

后续新增网站时，直接编辑 `index.html` 中的 `projects` 配置数组即可。
