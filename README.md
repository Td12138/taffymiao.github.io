# Taffy's Personal Blog

我的个人博客 - 记录学习、生活和思考

**在线访问:** https://Td12138.github.io/taffymiao.github.io/

---

## 特性

- 极简留白风格
- 温和中性色配色
- 📱 响应式设计，支持移动端
- 轻量滚动与渐显动画
- 🚀 GitHub Pages 托管

---

## 📁 项目结构

```
taffymiao.github.io/
├── index.html      # 主页
├── style.css       # 样式
├── script.js       # 交互脚本
├── README.md       # 说明文档
├── CNAME           # 自定义域名 (可选)
└── image_1.jpg     # 封面图片
```

---

## 🚀 本地开发

```bash
# 克隆仓库
git clone https://github.com/Td12138/taffymiao.github.io.git

# 进入目录
cd taffymiao.github.io

# 在浏览器中打开 index.html
# 或使用本地服务器
python3 -m http.server 8000
```

---

## 添加文章

在 `index.html` 的 `post-list` 部分添加：

```html
<article class="post-card">
    <p class="post-date">2026-03-XX</p>
    <h3>文章标题</h3>
    <p>文章简介...</p>
    <a href="article-link.html" class="read-more">阅读全文</a>
</article>
```

---

## 自定义

### 修改颜色

编辑 `style.css` 中的 CSS 变量：

```css
:root {
    --bg: #f5f2ea;
    --surface: rgba(255, 255, 255, 0.78);
    --text: #1c1a17;
    --muted: #6f685f;
}
```

### 修改个人信息

在 `index.html` 中修改：
- 邮箱地址
- GitHub 链接
- 个人介绍
- 技能列表

---

## 部署

```bash
# 提交更改
git add .
git commit -m "更新博客内容"

# 推送到 GitHub
git push origin main
```

---

## 技术栈

- HTML5
- CSS3
- JavaScript (原生)
- GitHub Pages

---

## 许可证

MIT License

---

**© 2026 Taffy** | Built with patience and clarity.
