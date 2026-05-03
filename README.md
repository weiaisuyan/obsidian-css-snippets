# obsidian-css-snippets
# Obsidian CSS Snippets

# Obsidian CSS 样式合集

一套专为 Obsidian 打造的界面优化 CSS 片段，解决表格排版、图片展示、长内容滚动等常见体验问题，让笔记阅读与编辑更舒适。

## 样式文件与详细功能说明

### 1. sticky-table-header.css
**功能：表格滚动固定表头**
- 滚动表格时，表头自动吸附在页面顶部，不会随内容滚动消失
- 清晰查看每一列数据对应的标题，大幅提升长表格阅读体验
- 兼容 Obsidian 原生表格与第三方插件渲染的 el-table 表格
- 适配浅色/深色主题，不遮挡、不重叠、不透明错乱
- 仅作用于表格，不影响页面其他内容布局

### 2. table-wrap.css
**功能：表格内容自动换行**
- 解决表格因文字过长被无限拉长、超出屏幕的问题
- 自动根据单元格宽度折行，保持表格整体美观
- 不破坏表格结构，不压缩关键内容
- 提升窄屏设备上的表格可读性
- 兼容所有 Markdown 表格语法

### 3. wide-scroll.css
**功能：优化宽内容横向滚动**
- 允许超长表格、大图、宽代码块横向滚动展示
- 不强制文字换行，保留内容原始排版
- 滚动条样式更美观、占用空间更小
- 大幅提升宽表格、流程图、数据表的展示效果
- 阅读模式与实时预览模式均生效

### 4. img-limit.css
**功能：图片尺寸限制与悬浮预览**
- 全局限制图片最大宽度，避免超大图片撑破页面排版
- 表格内图片自动缩小展示，防止表格被图片撑开变形
- 支持鼠标悬浮预览，查看完整高清大图
- 动画平滑、无闪烁、无卡顿
- 不影响图片查看、复制与拖拽操作

## 使用方法
1. 下载需要的 .css 样式文件
2. 将文件放入 Obsidian 仓库中的 .obsidian/snippets/ 文件夹
3. 打开 Obsidian → 设置 → 外观 → 找到对应片段并启用
4. 切换视图或重启 Obsidian 即可完整生效

## 适用环境
- Obsidian 桌面端
- 阅读模式 / 实时预览模式
- 兼容大部分第三方主题
- 兼容主流表格增强插件

## 开源协议
MIT License


# Obsidian CSS Snippets

A collection of professional CSS snippets for Obsidian, designed to improve tables, images, scrolling, and overall reading experience in daily note-taking.

## Detailed Features

### 1. sticky-table-header.css
**Sticky Table Header on Scroll**
- Keep table headers fixed at the top while scrolling through long tables
- Always know which column you are viewing, greatly improving data readability
- Compatible with native Obsidian tables and el-table plugin-rendered tables
- Works with light/dark mode without transparency issues
- No interference with other parts of the interface

### 2. table-wrap.css
**Auto Line Wrap for Table Cells**
- Prevent tables from overflowing screen due to long text
- Automatically wrap content inside cells to keep layout clean
- Maintain table structure without squeezing content
- Improve readability on narrow screens
- Fully compatible with standard Markdown tables

### 3. wide-scroll.css
**Enhanced Horizontal Scroll**
- Allow wide tables, large images, and long code blocks to scroll horizontally
- Preserve original layout without forced text wrapping
- Beautiful and lightweight scrollbar style
- Perfect for wide data tables, flowcharts, and wide content
- Works in both Reading View and Live Preview

### 4. img-limit.css
**Image Size Limit & Hover Preview**
- Globally limit maximum image width to avoid broken layout
- Auto-shrink images inside tables to keep table structure
- Hover to preview full-size high-definition images
- Smooth animation without flickering
- Does not affect image copying, dragging, or linking

## How to use
1. Download the .css file you need
2. Place it in the .obsidian/snippets/ folder of your vault
3. Open Obsidian → Settings → Appearance → Enable the snippet
4. Switch view or restart Obsidian to apply

## Compatibility
- Obsidian Desktop
- Reading View & Live Preview
- Most third-party themes
- Popular table-enhancing plugins

## License
MIT License
