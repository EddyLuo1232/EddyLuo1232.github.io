# Eddy Luo - 响应式个人主页

这是一个现代化的响应式个人主页，专为学术研究人员设计，完美适配桌面端、平板和移动设备。

## 🌟 特性

### 响应式设计
- **移动端优化**：完美适配手机、平板和桌面设备
- **流式布局**：内容自动调整适应不同屏幕尺寸
- **触摸友好**：优化的触摸交互体验

### 现代UI设计
- **渐变背景**：美观的Hero区域渐变设计
- **卡片布局**：清晰的信息层次结构
- **平滑动画**：页面滚动和元素加载动画
- **悬停效果**：丰富的交互反馈

### 导航功能
- **固定导航栏**：滚动时透明度变化效果
- **移动端汉堡菜单**：平滑的侧边菜单展开
- **平滑滚动**：点击导航链接平滑跳转到对应区域
- **返回顶部按钮**：方便快速回到页面顶部

### 交互功能
- **邮箱复制**：点击邮箱链接自动复制到剪贴板
- **语言切换**：支持多语言切换框架
- **键盘导航**：完整的键盘无障碍访问支持
- **打印样式**：优化的打印布局

## 📱 响应式断点

- **桌面端**: > 1024px - 完整的网格布局和侧边导航
- **平板端**: 768px - 1024px - 调整的网格和简化导航
- **移动端**: < 768px - 单列布局和汉堡菜单
- **小屏幕**: < 480px - 进一步优化的紧凑布局

## 🛠️ 技术栈

- **HTML5**: 语义化标记和无障碍性
- **CSS3**: 
  - Flexbox和CSS Grid布局
  - CSS自定义属性
  - 媒体查询响应式设计
  - CSS动画和过渡效果
- **JavaScript**: 
  - 原生ES6+
  - 交互功能和动画
  - 移动端菜单控制
  - 无障碍性支持

## 📁 文件结构

```
page_self/
├── index.html              # 主HTML文件
├── styles.css              # 响应式CSS样式  
├── script.js               # JavaScript交互功能
├── images/                 # 图片资源
│   ├── assets/             # 通用图片（头像、图标等）
│   │   ├── profile.jpg     # 主要头像照片
│   │   ├── eddy_anime.png  # 动漫头像
│   │   ├── rednote.png     # 小红书图标
│   │   ├── ttg.png         # 引用区域图片（右）
│   │   └── ttr.png         # 引用区域图片（左）
│   └── publications/       # 论文相关图片
│       ├── agrail.png      # AGrail论文图片
│       ├── jbv.png         # JailBreakV-28K论文图片
│       ├── cosmo.png       # COSMO论文图片
│       ├── teaser.png      # 动态防护论文图片
│       ├── overview.png    # 记忆推理论文图片
│       ├── vrp.png         # Visual-RolePlay论文图片
│       ├── autop.png       # Auto-Prompt论文图片
│       └── doxing_via_the_lens.png # Doxing论文图片
├── docs/                   # 文档和文件
│   ├── pdfs/               # PDF文档
│   │   ├── CV_Eddy.pdf     # 简历文件
│   │   └── doxing_via_the_lens.pdf # 研究论文
│   ├── README.md           # 文档结构说明
│   └── 头像设置说明.txt    # 头像设置说明
├── CNAME                   # GitHub Pages自定义域名
└── README.md               # 此说明文档
```

## 🚀 快速开始

1. **克隆或下载文件**
   ```bash
   # 确保所有文件在同一目录下
   ```

2. **替换个人信息**
   - 编辑 `index.html` 中的个人信息
   - 替换 `profile.jpg` 为您的个人头像
   - 更新社交媒体链接

3. **自定义样式**
   - 在 `styles.css` 中调整颜色主题
   - 修改字体和间距设置
   - 自定义动画效果

4. **部署**
   - 上传到任何静态网站托管服务
   - 支持 GitHub Pages、Netlify、Vercel 等

## 🎨 自定义选项

### 颜色主题
在 `styles.css` 文件顶部修改CSS变量：
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #667eea;
    --accent-color: #764ba2;
    --text-color: #333;
    --background-color: #f8fafc;
}
```

### 字体设置
```css
body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}
```

### 动画速度
```css
/* 调整动画持续时间 */
.hero-title {
    animation: fadeInUp 1s ease-out;
}
```

## 📧 联系信息设置

在HTML中更新您的联系信息：
```html
<a href="mailto:your.email@domain.com" class="social-link">
    <i class="fas fa-envelope"></i> Email
</a>
```

## 🔧 功能说明

### 移动端导航
- 汉堡菜单自动在768px以下显示
- 点击菜单项自动关闭侧边栏
- 支持ESC键关闭菜单

### 滚动动画
- 页面元素在进入视口时淡入
- 卡片元素的交错动画效果
- 导航栏滚动时背景变化

### 无障碍性
- 完整的键盘导航支持
- 屏幕阅读器优化
- 高对比度模式支持
- 动画减少模式支持

## 🌐 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- iOS Safari 12+
- Chrome Android 60+

## 📄 许可证

MIT License - 可自由使用和修改

## 🤝 贡献

欢迎提交 Issues 和 Pull Requests 来改进这个项目！

---

💡 **提示**: 记得定期更新您的学术成果和新闻动态，保持个人主页的时效性。 
