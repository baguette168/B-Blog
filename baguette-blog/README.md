# 个人博客网站https://baguette-ui.github.io/baguette-blog/

这是一个的个人博客网站。

## 项目特点

- 纯原生实现，无框架依赖
- 响应式设计，适配各种设备
- 现代化UI设计
- 优化的用户体验

## 布局方法说明

### 1. Flexbox布局
- 导航栏：使用`display: flex`实现水平布局，`justify-content: space-between`实现两端对齐
- 个人资料卡片：使用`flex-direction: column`实现垂直布局
- 导航链接：使用`gap`属性设置间距

### 2. Grid布局
- 卡片网格：使用`grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))`实现响应式网格
- 信息展示：使用Grid实现多列布局
- 表单布局：使用Grid实现两列表单布局

### 3. 定位方法
- 粘性定位：导航栏使用`position: sticky`实现滚动固定
- 相对定位：时间线项目使用`position: relative`作为定位上下文
- 绝对定位：时间线点使用`position: absolute`精确定位

### 4. 响应式设计
- 使用媒体查询`@media`适配不同屏幕尺寸
- 移动端优化：调整布局、字体大小和间距
- 弹性布局：使用`flex`和`grid`实现自适应布局

## 文件结构

```
├── index.html          # 首页
├── about.html          # 关于页面
├── resume.html         # 简历页面
├── hobby.html          # 摄影作品页面
├── css/
│   └── style.css       # 样式文件
└── images/            # 图片资源目录
```

