# Gabe SEO Portfolio

Gabe Ng Yen Wai 的个人主页，聚焦 SEO、GEO、AI Search Growth 与自动化实践。

网站采用原生 HTML、CSS 和 JavaScript 构建，无需安装框架或依赖，可直接部署到 GitHub Pages。

## 网站内容

- 个人简介与核心增长成果
- 工作经历与教育背景
- 8 个可拖动、可翻转的核心项目卡片
- SEO、GEO、LLM 内容架构与自动化技能
- 中文与英文全站切换
- 响应式桌面端与移动端布局
- Telegram 与 WhatsApp 联系入口
- 项目图片点击放大预览

## 核心项目

1. MCP 自动化连接 TG / 飞书
2. Python Indexing 工具
3. AI 关键词搭建
4. SEO 实战流量增长
5. GEO 优化
6. LLM 内容架构优化
7. Vibe Coding 页面
8. AI 手搓小游戏（个人爱好）

## 文件结构

```text
.
├── index.html    # 网站页面、样式与交互逻辑
├── profile.jpg   # 个人头像
├── game.png      # AI 小游戏项目截图
└── README.md     # 项目说明
```

图片必须与 `index.html` 放在同一目录，并保持文件名和大小写完全一致。GitHub Pages 会区分大小写。

## 本地预览

在项目目录运行：

```bash
python3 -m http.server 8000
```

然后访问：

```text
http://127.0.0.1:8000/
```

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库。
2. 将 `index.html`、`profile.jpg`、`game.png` 和 `README.md` 上传到仓库根目录。
3. 打开仓库的 `Settings` > `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`，然后点击 `Save`。
6. 等待 GitHub 完成部署后，打开 Pages 提供的网址。

更新文件后提交到 `main` 分支，GitHub Pages 会自动重新部署。图片未立即更新时，可等待几分钟后强制刷新浏览器。

## 技术栈

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages

## 作者

**Gabe Ng Yen Wai**  
SEO Manager · GEO Specialist · AI Search Growth
