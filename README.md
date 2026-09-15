# FreeWeb Tools

免费在线开发者工具集合，专注于提供快速、可靠、隐私友好的 Web 开发工具。

## 🚀 功能特性

### 在线工具
- **JSON Formatter** - JSON 格式化和验证
- **Base64 Encoder/Decoder** - Base64 编解码
- **CSS Shadow Generator** - CSS 阴影生成器
- **CSS Gradient Generator** - CSS 渐变生成器
- **Markdown Editor** - Markdown 编辑器
- **HTML Entity Encoder** - HTML 实体编码器

### SEO 博客
包含 6 篇针对工具的 SEO 优化文章，提升搜索引擎可见性。

## 📦 项目结构

```
freeweb-tools/
├── freeweb-online-tools.html  # 主应用文件
├── sitemap.xml                # 站点地图
├── robots.txt                 # 搜索引擎爬虫指引
├── _headers                   # Cloudflare Pages 安全头
├── _redirects                 # Cloudflare Pages 重定向规则
├── history/                   # 版本历史快照
│   ├── v1/
│   └── v2/
└── README.md
```

## 🛠️ 技术栈

- 纯 HTML/CSS/JavaScript，无需构建工具
- 响应式设计，支持移动端和桌面端
- 单文件应用，便于部署和维护

## 🚀 部署到 Cloudflare Pages

1. 在 GitHub 上 fork 或克隆此仓库
2. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. 进入 Pages 并创建新项目
4. 选择 GitHub 仓库并授权
5. 构建配置：
   - Build command: (留空)
   - Build output directory: `/`
6. 部署完成后，绑定自定义域名 `freeweb.eu.org`

## 📝 开发流程

### 添加新工具
1. 在 `freeweb-online-tools.html` 中添加新的工具区域
2. 在导航栏添加工具链接
3. 实现工具功能逻辑
4. 在 sitemap.xml 中添加新 URL

### 添加博客文章
1. 在 `blogPosts` 数组中添加新文章对象
2. 填写 title、excerpt、content 等字段
3. sitemap.xml 会自动更新（手动添加）

## 🔄 版本历史

- **v2** (2026-09-12) - 添加博客模块和 SEO 文章
- **v1** (2026-09-12) - 初始版本，包含 6 个在线工具

## 📄 许可证

MIT License

## 🔗 相关链接

- 项目网站：https://freeweb.eu.org
- Cloudflare Pages：https://pages.cloudflare.com
