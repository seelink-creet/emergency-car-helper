
# 药房学习助手统计系统 (Pharmacy Learning Assistant Stats)

## 项目简介
药房学习助手统计系统是一个轻量级的 Web 前端应用，旨在帮助药房从业人员或学习者快速记录、查看和管理学习过程中的关键数据。该工具通过直观的仪表盘展示准确率、易错药品追踪以及错题本积累，帮助用户科学复盘，提升业务水平。

## 主要功能
- **学习数据总览**：实时计算并显示测试准确率。
- **易错药品追踪**：快速定位并记录容易混淆的药品名称。
- **智能错题本**：管理错题条目，方便针对性强化练习。
- **一键重置**：支持快速清除所有统计数据，开启新一轮的复习计划。

## 技术栈
- **HTML5**: 构建页面结构。
- **Tailwind CSS**: 提供现代化的样式与响应式布局。
- **Vanilla JavaScript**: 处理核心统计逻辑与 DOM 更新。

## 如何使用

### 1. 本地运行
您可以直接在浏览器中打开 `index.html` 文件，或者使用任何静态服务器（如 VS Code 的 Live Server 插件）来运行该项目。

### 2. 界面操作
- **数据同步**：程序会自动根据内部状态计算准确率并更新页面数字。
- **数据重置**：点击页面底部的 **"重置统计数据"** 按钮，系统会弹出确认提示，点击确认后所有指标将归零，帮助您重新开始学习统计。

## 目录结构
```text
/
├── index.html       # 主页面，包含 HTML、CSS 和 JavaScript 核心逻辑
├── README.md        # 项目说明文档

```

## 贡献指南

如果您发现任何问题或有功能改进建议，欢迎提交 Issue 或 Pull Request：

1. Fork 本仓库。
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)。
3. 提交修改 (`git commit -m 'Add some AmazingFeature'`)。
4. 推送到分支 (`git push origin feature/AmazingFeature`)。
5. 开启一个 Pull Request。

## 许可证

本项目基于 [MIT 许可证](https://www.google.com/search?q=LICENSE) 开源，您可以自由使用、修改和分发。
