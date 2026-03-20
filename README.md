# 🎬 Kmeng AI Animata

> **The Local-First AI Video Production Studio for Creators.**
![chinese](README_CN.md)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-19-blue)
![Vite](https://img.shields.io/badge/Vite-6-purple)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-cyan)

---

## 📖 Introduction

**Kmeng AI Animata** is an open-source AI video creation tool designed to transform your local computer into a professional digital studio.

Built with a **Local-First** architecture, it leverages the File System Access API to read and write directly to your local drive, eliminating the need for cloud uploads and ensuring maximum data privacy. Deeply integrated with state-of-the-art models like **Volcengine (Doubao)** and **Vidu**, it provides a streamlined workflow from character design and scene building to final video generation.

## ✨ Key Features

### 🎨 Character Design
Generate stable, consistent character sheets with specific traits, solving the "inconsistent character" problem in AI art.
*   **Multi-Style Support**: Built-in presets for Anime, 3D Game, Oil Painting, Photorealistic, and more.
*   **Batch Generation**: Concurrently generate multiple variations to quickly select the best one.
*   **High Fidelity**: Supports 4K resolution character generation.

### 🏙️ Scene Creation
Build high-fidelity background environments for your stories with flexible aspect ratios.
*   **Custom Ratios**: Supports Landscape (16:9), Portrait (9:16), or Square (1:1).
*   **Style Consistency**: Share style parameters with characters to ensure visual harmony.

### 📦 Item Design
Generate props, weapons, or decorations to enrich your world details.
*   **Diverse Types**: Generate weapons, equipment, furniture, food, and more.
*   **Style Matching**: Automatically adapts to the project's overall art style.
*   **Visual Enhancement**: Use items as reference materials to add detail to your video generation.

### 🎥 Video Generation
Powered by Vidu models, offering cinematic control over video generation.
*   **Image-to-Video**:
    *   **Start Frame Control**: Define the opening shot to perfectly match your static assets.
    *   **Start & End Frame Control**: Specify both start and end points for precise narrative direction and transitions.
*   **Text-to-Video**: Generate dynamic video clips directly from text descriptions.
*   **Camera Control**: Adjust camera movement parameters (pan, tilt, zoom) for cinematic effects.

### 📂 Smart Asset Management
Manage AI assets like local files—no more messy libraries.
*   **Auto-Archiving**: Generated characters and scenes are automatically sorted into corresponding `assets/` directories.
*   **Visual Gallery**: Masonry-style browser for quick previewing and drag-and-drop.
*   **Metadata Tracking**: Automatically saves prompts and parameters for every generation, allowing easy reproduction.

## ⚡ Quick Start

### Prerequisites
*   **Node.js** (v18+)
*   Modern Browser (Chrome or Edge recommended)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/kmengai-animata.git

# 2. Enter the directory
cd kmengai-animata

# 3. Install dependencies
npm install

# 4. Start development server
npm run dev
```

Visit `http://localhost:5173` to start creating.

## 📖 Usage Workflow

Start your production in just four steps:

1.  **Configure Engine**: Enter your Volcengine or Vidu API Key in **Settings** (keys stored locally in LocalStorage).
2.  **Create Project**: Select a local folder as your project root to store all assets.
3.  **Prepare Assets**: Use **Character** or **Scene** modules to generate and finalize your art assets.
4.  **Produce Video**: Go to **Fragment** module, select generated images as start frames, describe the action, and generate video.

## 🛠️ Tech Stack

*   **Frontend Framework**: [React 19](https://react.dev/)
*   **Build Tool**: [Vite](https://vitejs.dev/)
*   **UI Library**: [HeroUI](https://www.heroui.com/)
*   **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
*   **Animation**: [Framer Motion](https://www.framer.com/motion/)
*   **Routing**: [React Router](https://reactrouter.com/)
*   **Language**: [TypeScript](https://www.typescriptlang.org/)

## 🤝 Contributing

Issues and Pull Requests are welcome!

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## focus

| wechat official account | wechat group |
|--------|--------|
| ![wechat official account](https://biyebang.com.cn/upload/wechat_Official-Account.png) | ![wechat group](https://biyebang.com.cn/upload/wechat_group.jpg) |
