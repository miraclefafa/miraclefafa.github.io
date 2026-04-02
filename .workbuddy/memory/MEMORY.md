# 项目长期记忆

## 项目概览
- 项目：中国海洋大学 AIMM@OUC 实验室官网
- 路径：`c:/Users/18239/Desktop/laboratory-website`
- 技术栈：纯 HTML + CSS + JS（无框架）
- 主色调：`--primary-color: #0066cc`，`--secondary-color: #004499`，`--accent-color: #0099ff`

## 已完成的主要工作
- **Logo 集成初版（2026-03-26）**：将 `AIMM6.jpg` 加入导航栏和 Hero 横幅。
- **Hero 区域重设计（2026-03-26）**：用户反馈 logo 太小，进行全面重设计：
  - 导航栏 Logo：40px → **52px 圆形**展示（border-radius: 50%），品牌区改为双行文字（主名称+副标题 Ocean University of China）
  - Hero 区域：单列居中 → **左右分栏布局**（`.hero-logo-col` 左侧 280px 大Logo + `.hero-text-col` 右侧文字）
  - Hero 背景：重设为深海多层渐变（radial-gradient 叠加 linear-gradient），加入 `::before` 动态光晕动画、`::after` 水平线纹理层
  - 标题改为渐变文字（`-webkit-background-clip: text`）
  - 响应式：992px → 垂直单列 200px Logo；768px → 150px Logo；480px → 120px Logo

## 设计约定
- Logo 文件：`AIMM6.jpg`（精细圆形徽章设计，蓝色海洋/AI 主题）
- 导航栏 Logo class：`.nav-logo-wrap`（52px 圆形）/ `.nav-logo-img`
- Hero 布局 class：`.hero-logo-col`（左侧 Logo 列）/ `.hero-text-col`（右侧文字列）/ `.hero-logo-wrap`（280px 圆形）
- 响应式断点：992px（平板折叠为垂直）、768px、480px
- 本地预览：`python -m http.server 3200`（端口 3200）
