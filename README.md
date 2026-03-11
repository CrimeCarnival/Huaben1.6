📚 Crous Library Pro v3.4
一个零依赖、纯本地、跨平台的私有书库与创意工具箱

Crous Library Pro 是一款完全基于浏览器本地环境运行的现代化阅读与图书管理系统。它不需要任何后端服务器，无需注册，所有数据绝对私有化。凭借纯 HTML/JS 单文件架构，它实现了从桌面端到移动端的全平台无缝适配，并创新性地集成了「Crous 创意工具集」，为你提供从阅读、做笔记到有声书剧本排版、画册制作的一站式体验。

✨ 核心亮点 (Features)
📖 1. 全格式沉浸式阅读器
多格式支持：完美支持 EPUB、PDF、TXT 和 Markdown 格式。

极致排版：支持自定义字体大小、字间距，提供单页/双页阅读模式切换。

护眼主题：内置默认、杏仁黄、豆沙绿、极客灰四款主题背景，并支持全局夜间模式。

高级笔记系统：支持 EPUB/PDF 文本高亮划线、添加心得批注，并可一键将全书笔记导出为 Markdown 文件。

📱 2. 全平台兼容与离线访问 (Smart Fallback)
无论你使用什么设备，都能获得最佳体验：

PC 端 (Chrome/Edge)：利用最新的 File System Access API，无缝扫描本地文件夹，不占用额外浏览器缓存空间。

Mac 端 (Safari)：智能降级使用 webkitdirectory 文件夹导入。

移动端 (iOS/Android)：响应式抽屉侧边栏，支持多文件直接导入。

持久离线：在 Mac 和移动端导入的书籍，其文件实体（Blob）将永久加密缓存在本地 IndexedDB 中，断网环境下依然可以流畅阅读。

🛠️ 3. 内置 Crous 创意工具集
不仅是阅读器，更是创作者的左膀右臂：

像素工坊 (Pixel Workshop)：专业的图片批处理与排版工具。支持多图预览、自定义画布尺寸（A4/A5/各类相纸）、DPI设置、边距微调、一键旋转，最终批量导出为高清 PDF（非常适合漫画整理与打印排版）。

智能画本 (Smart Storybook)：为有声演播和剧本创作者打造。一键智能识别剧本角色并自动分配高亮颜色，支持手动着色微调，带格式复制到任何编辑器中。

🔐 4. 极致的隐私与数据安全
零服务器交互：没有任何数据会被上传到云端，你的书库和笔记只存在于你设备的本地数据库（IndexedDB）中。

数据自由流转：支持一键导出/导入书库索引，随时备份或迁移你的阅读进度和藏书数据。

🚀 快速开始 (Usage)
本项目的最大特色在于其极简的部署方式：

下载文件：获取 Somnia Library Pro.html 文件。

直接运行：使用任何现代浏览器（Chrome / Edge / Safari / Firefox）双击打开该 HTML 文件即可使用。

部署至网站（可选）：你可以将该文件托管在 GitHub Pages、Vercel 等任何静态网页托管平台上，作为你的云端个人书库入口（数据依然保存在访问者的本地）。

💻 技术栈 (Tech Stack)
UI 框架：Tailwind CSS + 纯原生 CSS (跨组件隔离)

图标库：FontAwesome

核心依赖：

pdf.js (PDF渲染)

epub.js (EPUB解析引擎)

marked.js (Markdown渲染)

jsPDF (PDF生成与导出)

本地存储：IndexedDB API, LocalStorage

文件系统：File System Access API (Native Desktop) & Webkit Directory Fallback (Mobile/Safari)

💖 赞赏与支持
如果你觉得 Crous Library Pro 改善了你的阅读体验，或者提升了你的创作效率，欢迎点击侧边栏左下角的 「赞赏支持 Somnia」 请作者喝杯咖啡 ☕️，你的支持是我持续优化的最大动力！
