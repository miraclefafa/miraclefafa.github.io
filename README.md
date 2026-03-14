# Ihcil@OUC 实验室官网

简洁大方美观的静态实验室网站，基于纯 HTML + CSS + JavaScript 构建。

## 项目结构

```
laboratory-website/
├── index.html          # 主页面
├── css/
│   └── style.css      # 样式文件
├── js/
│   └── script.js      # 脚本文件
└── README.md          # 说明文档
```

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件即可查看网站
2. 推荐使用现代浏览器（Chrome、Firefox、Edge、Safari）获得最佳体验

## 功能特性

- **响应式设计**：完美适配桌面端、平板和移动设备
- **平滑滚动**：点击导航链接平滑滚动到对应区块
- **动态导航**：导航栏随滚动自动高亮当前区域
- **动画效果**：元素进入视口时有优雅的淡入动画
- **移动端菜单**：支持汉堡菜单，方便移动端导航

## 页面板块

1. **首页横幅** - 展示实验室简介和核心愿景
2. **关于我们** - 详细介绍实验室背景和研究领域
3. **研究方向** - 海洋预报、雷达预报、智能预警
4. **团队成员** - 展示导师信息和毕业生名单
5. **发表论文** - 展示最新的学术研究成果
6. **近期动态** - 新闻和活动动态
7. **联系我们** - 联系方式和友情链接

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Edge
- Safari
- 其他现代浏览器

## 技术栈

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- 响应式设计

## 自定义说明

### 修改颜色主题

在 `css/style.css` 文件中修改 `:root` 变量：

```css
:root {
    --primary-color: #0066cc;      /* 主色调 */
    --secondary-color: #004499;     /* 次色调 */
    --accent-color: #0099ff;        /* 强调色 */
    /* ... 其他颜色变量 */
}
```

### 修改内容

- **文本内容**：直接编辑 `index.html` 中的文本
- **图片**：替换 `img` 标签的 `src` 属性
- **链接**：修改 `a` 标签的 `href` 属性

### 添加新的团队成员

在 HTML 中复制 `.team-card` 元素并修改内容：

```html
<div class="team-card professor">
    <div class="team-avatar">
        <img src="头像图片URL" alt="姓名">
    </div>
    <div class="team-info">
        <h3>姓名</h3>
        <p class="team-role">职位</p>
        <p class="team-email">邮箱</p>
        <!-- ... -->
    </div>
</div>
```

## 部署

可以直接部署到任何静态网站托管服务：

- GitHub Pages
- Netlify
- Vercel
- 或任何支持静态文件的服务器

## 许可证

本网站代码可自由使用和修改。
