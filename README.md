# emblulol · 个人主页

> 在分子与像素间寻找秩序 —— 以科研的严谨解构世界，以镜头的诗意重构光影

分析化学研究者与摄影艺术家的跨领域个人主页，展示科研能力与视觉作品的交汇点。

## 技术栈

- 纯 HTML/CSS/JS，单文件，零依赖框架
- 深色科技感设计（#0b0f19），双色主题：科技青蓝 #00d4ff + 暖阳金 #f5a623
- 毛玻璃卡片效果 (Glassmorphism)
- 完全响应式（移动端优先）
- Intersection Observer 导航高亮
- Google Fonts: Inter + Space Grotesk
- Font Awesome 6 图标

## 本地预览

直接用浏览器打开 `index.html`，或使用任意静态服务器：

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .
```

然后访问 `http://localhost:8000`

## 部署到 GitHub Pages

1. 在 GitHub 创建仓库（如 `username.github.io` 或任意仓库名）
2. 推送代码：

```bash
git remote add origin https://github.com/你的用户名/仓库名.git
git branch -M main
git push -u origin main
```

3. 在仓库 **Settings → Pages** 中：
   - Source: **Deploy from a branch**
   - Branch: `main` / `/(root)`
   - 点击 Save

4. 几分钟后访问 `https://你的用户名.github.io/仓库名/`

## 需要替换的内容

代码中用中文注释标出了所有占位项（搜索"可替换"）：

| 项目 | 当前值 | 说明 |
|------|--------|------|
| 姓名 | emblulol | 导航栏、Hero、页脚 |
| 邮箱 | yyaoyyao42@gmail.com | 联系表单、社交图标 |
| 社交链接 | `#` | GitHub / 图虫 / 微博 |
| 项目链接 | `#`（data-link 属性） | 4 个作品卡片 |
| 项目图片 | Font Awesome 图标 | 替换为 `<img>` 标签 |
| 版权年份 | 2026 | 页脚 |

## 许可

MIT
