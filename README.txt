# 一键汇率（PWA）v2
修复：部分接口返回不含 rates 导致报错（reading 'CNY'）。
改为双数据源：
- 主：open.er-api.com/v6/latest/USD（Open Access）
- 备：api.frankfurter.app/latest（ECB reference，非严格实时）

部署：把 index.html / manifest.json / sw.js 放到站点根目录发布即可。
