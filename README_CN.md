# 🎬 Kmeng AI Animata (可梦 AI 漫剧版)

> **专为创作者打造的本地优先 (Local-First) AI 视频创作工作台。**
[english](README.md)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-19-blue)
![Vite](https://img.shields.io/badge/Vite-6-purple)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-cyan)

---

## 📖 项目简介

**Kmeng AI Animata** 是一款开源的 AI 视频创作工具，旨在将您的本地电脑转化为专业的数字片场。

它采用 **Local-First（本地优先）** 架构，通过浏览器的 File System Access API 直接读写本地文件，无需上传素材至云端，最大程度保障数据隐私。项目深度集成了 **火山引擎 (Doubao)** 和 **Vidu** 等前沿大模型，提供从角色设定、场景构建到视频生成的全流程辅助，帮助创作者高效制作动画短片。

## ✨ 核心功能

### 🎨 角色设计 (Character Design)
稳定生成具有固定特征的角色立绘，解决 AI 绘画“角色不一致”的痛点。
*   **多风格支持**：内置二次元、3D 游戏、油画、写实等多种风格预设。
*   **批量生成**：支持并发生成多张方案，快速筛选最佳结果。
*   **超清画质**：支持生成 4K 分辨率的角色原画。

### 🏙️ 场景构建 (Scene Creation)
为故事生成高保真的背景环境，支持多种构图比例。
*   **自定义比例**：支持横屏 (16:9)、竖屏 (9:16) 或方形 (1:1) 构图。
*   **风格统一**：可与角色使用相同的风格参数，确保画面视觉的一致性。

### 📦 物品设计 (Item Design)
生成游戏道具、武器或装饰物，完善世界观细节。
*   **类型丰富**：支持生成武器、装备、家具、食物等多种类型的道具。
*   **风格匹配**：自动适配项目整体的美术风格，确保与角色和场景的协调。
*   **辅助创作**：生成的物品可作为视频生成的参考素材，增加画面细节。

### 🎥 视频生成 (Video Generation)
基于 Vidu 模型，提供电影级的视频生成控制能力。
*   **图生视频 (Image-to-Video)**：
    *   **首帧控制**：指定视频起始画面，完美衔接静态素材。
    *   **首尾帧控制**：同时指定起始和结束画面，精准控制剧情走向和转场。
*   **文生视频 (Text-to-Video)**：通过文字描述直接生成动态视频片段。
*   **运镜控制**：支持推拉摇移等运镜参数调节。

### 📂 智能资产管理 (Asset Management)
像管理本地文件一样管理 AI 资产，告别混乱的素材库。
*   **自动归档**：生成的角色、场景自动分类存入 `assets/` 下的对应目录。
*   **可视化画廊**：提供瀑布流式素材浏览界面，支持快速预览和拖拽。
*   **元数据追踪**：自动保存生成时的提示词 (Prompt) 和参数，方便随时回溯复现。

## ⚡ 快速开始

### 环境要求
*   **Node.js** (v18+)
*   现代浏览器 (推荐 Chrome 或 Edge)

### 安装步骤

```bash
# 1. 克隆项目
git clone https://github.com/your-username/kmengai-animata.git

# 2. 进入目录
cd kmengai-animata

# 3. 安装依赖
npm install

# 4. 启动开发服务器
npm run dev
```

启动后访问 `http://localhost:5173` 即可使用。

## 📖 使用流程

只需四步，即可开始您的创作之旅：

1.  **配置引擎**：在 **设置** 中填入火山引擎或 Vidu 的 API Key（密钥仅存储于本地 LocalStorage）。
2.  **创建项目**：选择一个本地文件夹作为项目根目录，用于存储所有素材。
3.  **筹备素材**：进入 **角色** 或 **场景** 模块，生成并确认您的美术资产。
4.  **制作视频**：进入 **片段** 模块，选择生成的图片作为首帧，描述动作并生成视频。

## 🛠️ 技术栈

*   **前端框架**: [React 19](https://react.dev/)
*   **构建工具**: [Vite](https://vitejs.dev/)
*   **UI 组件库**: [HeroUI](https://www.heroui.com/)
*   **样式方案**: [Tailwind CSS v4](https://tailwindcss.com/)
*   **动画库**: [Framer Motion](https://www.framer.com/motion/)
*   **路由**: [React Router](https://reactrouter.com/)
*   **语言**: [TypeScript](https://www.typescriptlang.org/)

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE) 开源。

## 关注一下

| 公众号 | 交流群 |
|--------|--------|
| ![公众号](https://biyebang.com.cn/upload/wechat_Official-Account.png) | ![交流群](https://biyebang.com.cn/upload/wechat_group.jpg) |
