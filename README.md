<div align="center">

# 🧮 Sorting Algorithm Visualizer

**Watch the world's top 5 sorting algorithms race side-by-side.**

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-06b6d4?style=for-the-badge&logo=githubpages&logoColor=white)](https://nwfella.github.io/sorting-algorithms-viz/)
[![License: MIT](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)

<img src="https://nwfella.github.io/sorting-algorithms-viz/assets/screenshot.png" alt="Screenshot" width="700"/>

</div>

---

## 🚀 Live Demo

**[→ nwfella.github.io/sorting-algorithms-viz](https://nwfella.github.io/sorting-algorithms-viz/)**

No install required. Open the link, hit **Run**, and watch all 5 algorithms sort the same random array simultaneously.

---

## 📊 Algorithms

### Row 1 — Classics

| # | Algorithm | Complexity | Color |
|---|-----------|-----------|-------|
| 1 | **Bubble Sort** | O(n²) | ![](https://via.placeholder.com/12/06b6d4/06b6d4) Cyan |
| 2 | **Selection Sort** | O(n²) | ![](https://via.placeholder.com/12/8b5cf6/8b5cf6) Purple |
| 3 | **Insertion Sort** | O(n²) | ![](https://via.placeholder.com/12/10b981/10b981) Green |
| 4 | **Merge Sort** | O(n log n) | ![](https://via.placeholder.com/12/f59e0b/f59e0b) Amber |
| 5 | **Quick Sort** | O(n log n) | ![](https://via.placeholder.com/12/ec4899/ec4899) Pink |

### Row 2 — Fresh

| # | Algorithm | Complexity | Color |
|---|-----------|-----------|-------|
| 6 | **Heap Sort** | O(n log n) | ![](https://via.placeholder.com/12/ff6b6b/ff6b6b) Coral |
| 7 | **Cocktail Shaker** | O(n²) | ![](https://via.placeholder.com/12/a29bfe/a29bfe) Lavender |
| 8 | **Radix Sort (LSD)** | O(nk) | ![](https://via.placeholder.com/12/55efc4/55efc4) Mint |
| 9 | **Shell Sort** | O(n·log²n) | ![](https://via.placeholder.com/12/fd79a8/fd79a8) Salmon |
| 10 | **Gnome Sort** | O(n²) | ![](https://via.placeholder.com/12/fab1a0/fab1a0) Peach |

---

## ✨ Features

- **Side-by-side comparison** — all 5 algorithms start on the same random data so you can see speed & behavior differences in real time
- **Horizontally scrollable** — fits any screen. Scroll arrows + dot indicators + snap scrolling on mobile
- **Live stats** — comparison count, swap count, and elapsed time for each algorithm
- **Adjustable array size** — 10 to 100 elements
- **Speed control** — slow-mo to lightning fast
- **Color-coded visualization** — comparing (cyan), swapping (pink), pivot (yellow), merging (orange), sorted (green)
- **Dark cyberpunk theme** — gradient bars with glow effects, grid background, smooth animations
- **Zero dependencies** — single `index.html`, self-contained, works offline

---

## 🛠 Usage

1. Open the **[live demo](https://nwfella.github.io/sorting-algorithms-viz/)**
2. Choose array **Size** (default: 50)
3. Adjust **Speed** with the slider
4. Click **▶ Run** to start all algorithms
5. Watch them race! Scroll horizontally if they don't all fit on screen
6. Click **↺ Reset** to generate a new random array

---

## 🧠 How It Works

Each algorithm runs as a JavaScript **generator function** that yields its state at every comparison and swap. A shared animation loop steps through all generators simultaneously, redrawing the canvas after each tick. This ensures every algorithm sees the same random array and advances at the same pace.

---

## 📄 License

[MIT](LICENSE) — feel free to use, modify, and share.

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/nwfella">nwfella</a></sub>
</div>
