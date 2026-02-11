# 一键汇率（PWA）
- 点一次“刷新汇率”抓取 USD/CNY/JPY/THB 最新汇率，并显示交叉汇率
- 可作为网站托管（GitHub Pages / Cloudflare Pages / Netlify 等）
- 支持“添加到主屏幕”（PWA），离线可打开页面壳（离线时无法刷新）

## 部署到 GitHub Pages（最简）
1. 新建一个仓库（public/private 都行）
2. 上传：index.html / manifest.json / sw.js
3. Settings → Pages
4. Source 选 Deploy from a branch；Branch 选 main；Folder 选 /(root)
5. 保存后会出现访问链接（如 https://<用户名>.github.io/<仓库名>/ ）

## 使用
- 手机打开链接
- iPhone：分享 → 添加到主屏幕
- Android：菜单 → 添加到主屏幕

数据源：exchangerate.host 的 latest 接口（base=USD）
