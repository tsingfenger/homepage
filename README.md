# 个人主页

一个简洁美观的个人主页模板，支持亮/暗主题切换。

## ✨ 特色功能

- **亮色/暗色模式切换**
- **多套主题样式**
- **响应式设计**，支持桌面端和移动端
- **背景模糊效果**，可通过 CSS 配置
- 使用**原生 HTML、CSS、JS**，无框架依赖
- **动画效果**，流畅的交互体验

## 🛠️ 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- SVG 图标

## 📁 项目结构

```
homepage/
├── index.html          # 主页面
├── static/
│   ├── css/
│   │   ├── root.css    # 主题配置
│   │   └── style.css   # 样式文件
│   ├── js/
│   │   └── script.js   # 功能脚本
│   ├── img/            # 图片资源
│   ├── fonts/          # 字体文件
│   └── svg/            # SVG 图标
└── docker-compose.yaml # Docker 部署配置
```

## 🚀 快速开始

1. **直接访问**
   ```bash
   # 克隆项目
   git clone https://github.com/your-username/homepage.git
   cd homepage
   
   # 用浏览器打开 index.html
   open index.html
   ```

2. **Docker 部署**
   ```bash
   # 使用 Docker Compose
   docker compose up -d
   ```

## ⚙️ 配置说明

### 主题配置
编辑 `static/css/root.css` 文件来自定义主题样式：
- 修改颜色变量
- 调整背景样式
- 配置模糊效果

### 个人信息
编辑 `index.html` 文件来修改：
- 个人介绍
- 项目展示
- 联系方式链接

### 项目图标
现在使用 Emoji 图标，可在 HTML 中直接修改：
```html
<span class="project-emoji">🔧</span>
```

## 📱 响应式支持

- **桌面端**：4列网格布局
- **平板端**：2列布局
- **移动端**：单列布局，侧边栏可收起

## 🎨 自定义

### 添加新项目
复制现有项目块，修改标题、描述和图标：
```html
<a class="projectItem" href="your-link">
    <div class="projectItemLeft">
        <h1>项目名称</h1>
        <p>项目描述</p>
    </div>
    <div class="projectItemRight">
        <span class="project-emoji">🚀</span>
    </div>
</a>
```

### 修改配色
在 `static/css/root.css` 中调整 CSS 变量：
```css
html {
    --main_text_color: #your-color;
    --item_bg_color: #your-bg-color;
    /* 更多变量... */
}
```

## 📄 许可证

本项目基于原作者的开源版本进行修改，遵循相应的开源协议。

## 🙏 致谢

感谢原作者提供的优秀模板基础。


