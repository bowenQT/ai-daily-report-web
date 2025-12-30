# AI 行业资讯快报

自动生成的 AI 行业资讯快报网站。

## 功能特点

- 📰 自动聚合多渠道 AI 资讯
- 💡 AI 生成的编辑点评和趋势解读
- 📊 投融资数据可视化
- 🏷️ 热点词云
- 🌙 深色/浅色主题切换
- 📱 响应式设计，支持移动端

## 信息来源

### 国内媒体
- 极客公园、InfoQ、硅星人Pro、甲子光年、MacTalk
- 暗涌Waves、十字路口Crossing、阑夕
- 微信公众号 RSS（via 瓦斯阅读）

### 国际媒体
- TechCrunch、The Verge、Wired、Ars Technica
- MIT Technology Review

### AI/技术
- arXiv、Hugging Face、GitHub Trending
- OpenAI Blog、Anthropic News

### 投资/报告
- CB Insights、a16z Blog

## 部署

项目使用 Vercel 自动部署：

1. 将代码推送到 GitHub
2. 在 Vercel 中导入项目
3. 自动部署完成

## 本地预览

```bash
npx serve .
```

## 目录结构

```
ai-daily-report-web/
├── index.html          # 重定向到最新报告
├── reports/            # 历史报告
│   └── 2025-12-30.html
├── assets/
│   └── style.css       # 样式文件
├── vercel.json         # Vercel 配置
└── package.json
```

## License

MIT
