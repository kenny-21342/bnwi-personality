# BNWI 美丽新世界人格指标

《美丽新世界》主题的 32 题人格测试，包含 16 种人格结果。

## 本地预览

直接打开 `index.html`，或在此目录运行：

```sh
python3 -m http.server 8000
```

然后访问 http://localhost:8000。

## 部署与更新

此项目为纯静态 HTML，CSS、JavaScript 与 SVG 插图均内嵌在 `index.html` 中，无需安装依赖或构建。Google Fonts 为可选外部字体，加载失败时使用系统字体。

GitHub 仓库连接 Vercel 后，推送到 `main` 分支即自动更新生产网站。后续请修改本仓库中的 `index.html`。

也可在已关联 Vercel 的本地目录执行 `vercel --prod` 部署。
