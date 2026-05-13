# 🧽 Unique Paths Visualizer

A visual, interactive React application to explore **dynamic programming (DP)** and **shortest path algorithms**. Easily toggle between **Leetcode-style Unique Paths II** and **Dijkstra's shortest path**, build your own grid, and visualize the paths with animations.

### 🌐 Live Demo

> _https://greenmarioh.github.io/unique-paths-visualizer/_

---

## 📌 Features

- 🧠 **Unique Paths II (DP)**: Visualizes total valid paths using a dynamic programming table. Implements logic based on [LeetCode - Unique Paths II](https://leetcode.com/problems/unique-paths-ii/description/).
- 📏 **Shortest Path Mode**: Uses a modified Dijkstra’s algorithm that supports 8-directional movement (diagonals included) for pathfinding.
- 👡️ **Interactive Grid Editor**:
  - Click or drag to add/remove obstacles.
  - In shortest path mode, drag Start (🟩) and End (🟦) nodes freely.
- 🧮 **DP Table Rendering**: Optionally display the number of ways to reach each cell in unique paths mode.
- 🔁 **Path Animation**: Each cell in a computed path lights up sequentially to demonstrate traversal order.
- 📀 **Resizable Grid**: Supports grids from 1×1 to 12×12 with smooth resets and state preservation.
- ⚡ Fast and reactive UI thanks to React + Vite + Tailwind.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Vishnurockyedwards/unique_path_visualizer.git
cd unique-paths-visualizer
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Start Development Server

```bash
npm run dev
# or
yarn dev
```

Then open: [http://localhost:3000](http://localhost:3000)

---

## 🛠️ Built With

- ⚛️ **[React](https://reactjs.org/)** — UI component library
- 🔆 **[TypeScript](https://www.typescriptlang.org/)** — Typed JavaScript for safety and tooling
- 🎨 **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first CSS framework
- ⚡ **[Vite](https://vitejs.dev/)** — Lightning-fast build tool and dev server
- 📦 **Modular Architecture** — Reusable components (GridCell, InfoCard, etc.)
- 📁 **Single-File Visualizer Component** — Main logic lives in `UniquePathsVisualizer.tsx` for simplicity and portability

---

## 📄 License

MIT License. Feel free to fork and improve!

---

## 🚇️ Author

Created with ❤️ by [@the10thvishnu](https://github.com/Vishnurockyedwards)


