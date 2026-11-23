# 启航智学 · 竞赛攻略工作台

- `index.html`：工作台页面。
- `data.json`：竞赛数据，每天早上由自动任务更新后推送到这里，工作台的竞赛库和本月海报读它。

Netlify 部署：导入本仓库，Build command 留空，Publish directory 填 `.`。

在 Netlify 上打开时，AI 起草、AI 改稿助手和共享数据库不可用（它们只在 claude.ai 里能用），稿子只保存在各自的浏览器里。竞赛库、配图模板、规则出图、本月海报和导出图片都能用。
