# AnySearch comparison test tool

一键体验各家 AI Search API 的效果差异。

## 在线体验

直接访问 GitHub Pages 链接即可使用（部署后自动生成）。

## 功能

- 实时调用 AnySearch API 对比搜索效果
- 6 种预设测试场景（comparison research/财报/代码/安全/学术/中文）
- 7 家Comparison Playgrounds
- 评测维度参考 + 技术规格对比表

## 本地运行

```bash
# 方法1：直接打开 HTML
open index.html

# 方法2：启动本地服务（支持实际 API 调用）
python3 -m http.server 8899
# 然后打开 http://localhost:8899
```

## comparison清单

| 产品 | 测试入口 | 免费额度 |
|------|---------|---------|
| AnySearch | [控制台](https://anysearch.com/console/api-keys) | 1000次/天 |
| Exa | [Dashboard](https://dashboard.exa.ai) | 1000次/月 |
| Tavily | [Playground](https://app.tavily.com/playground) | 1000次/月 |
| Brave Search | [API Console](https://api.search.brave.com/app) | 2000次/月 |
| Serper | [Playground](https://serper.dev/playground) | 2500次/月 |

---

公开测试工具 · 2026-05-19*
