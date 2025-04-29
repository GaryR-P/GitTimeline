# GitTimeline

An interactive, educational web tool that visually simulates Git commit history and branching structures. Users type Git-like commands and see a live, dynamic SVG commit graph update based on their inputs.

---

## ✨ Features

- `git commit -m "message"` — Add a commit with a custom message.
- `git branch <branchname>` — Create a new branch from the current branch.
- `git checkout <branchname>` — Switch to an existing branch.
- `git merge <branchname>` — Merge a branch into the current branch, with a dashed merge line.
- Dynamic, colorful visualization of Git commit graphs.
- Tooltips on each commit showing commit messages.

---

## 📖 How It Works

1. **Type Git Commands**: Type Git-like commands into the input area (one per line).
2. **Submit**: Click the **Submit** button.
3. **Visualize**: The commit graph updates live, showing your simulated Git history.

Commands are parsed into an internal `branches` object. D3.js renders this object onto an SVG graph dynamically.

---

## 🛠️ Built With

- [Astro](https://astro.build/) — Static site generator for clean project structure
- [D3.js](https://d3js.org/) — SVG-based graph drawing
- [GitHub Pages](https://pages.github.com/) — Deployment

---

## 🚀 Live Demo

[https://GaryR-P.github.io/GitTimeline](https://GaryR-P.github.io/GitTimeline)

