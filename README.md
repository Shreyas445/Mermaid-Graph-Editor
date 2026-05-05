
# 🧜‍♂️ Mermaid Studio Pro

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg?style=for-the-badge)](https://shreyas445.github.io/Mermaid-Graph-Editor/)
[![Mermaid.js](https://img.shields.io/badge/Mermaid.js-ff3670?style=for-the-badge&logo=mermaid&logoColor=white)](#)
[![CodeMirror](https://img.shields.io/badge/CodeMirror-5.65.13-blue?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A premium, interactive visual editor for [Mermaid.js](https://mermaid.js.org/). 

Mermaid Studio Pro bridges the gap between code-based diagramming and visual whiteboard tools. It features a custom-built, interactive physics engine that allows you to drag, drop, and visually rearrange your Mermaid nodes while keeping the underlying SVG arrows perfectly connected via rubber-band interpolation.

<br>

### [-----> CLICK HERE TO OPEN LIVE WEBSITE](https://shreyas445.github.io/Mermaid-Graph-Editor/)
<br>
<br>

<img width="1855" height="946" alt="image" src="https://github.com/user-attachments/assets/8d49aca2-9355-42e0-8bb7-1e6eae1c91ae" />




## ✨ Key Features

* **🎨 Premium UI/UX:** A clean, minimalist interface featuring glassmorphism elements, custom scrollbars, and a distraction-free split-pane layout.
* **🌗 Dynamic Theming:** Seamlessly toggle between fully integrated Dark and Light modes.
* **🖱️ True Visual Editing:** Click the "Edit Visually" tool to physically drag nodes and subgraph clusters around the canvas.
* **🧲 Rubber-Band Physics:** A custom Euclidean distance engine ensures arrows dynamically stretch, bend, and stay glued to their respective nodes during visual dragging.
* **✏️ Sketch Mode:** Toggle the Pencil icon to apply a custom SVG displacement filter, giving your precise diagrams a hand-drawn, whiteboard aesthetic.
* **⚙️ Real-Time Config Engine:** Adjust node colors, borders, text, line colors, and drop-shadow intensities on the fly without resetting your layout.
* **↩️ Visual Undo History:** Made a mistake while dragging? Press `Ctrl+Z` to instantly revert your visual changes.
* **💾 High-Res Export:** Download your completed diagrams as crisp, scalable SVGs with a single click.

## 🛠️ Tech Stack

This project is built to be lightning-fast with zero build steps or heavy frameworks:
* **HTML5 / CSS3:** Utilizing CSS variables for instantaneous theme and color switching.
* **Vanilla JavaScript:** Powers the custom drag-and-drop physics, interpolation math, and state history.
* **Mermaid.js (v10+):** The core rendering engine for diagram syntax.
* **CodeMirror (v5):** Provides a robust, syntax-highlighted code editing experience.

## 🚀 Getting Started

Because this project uses vanilla web technologies, running it locally is incredibly simple.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/shreyas445/Mermaid-Graph-Editor.git](https://github.com/shreyas445/Mermaid-Graph-Editor.git)
   ```
2. **Open the project:**
   Simply double-click the `index.html` file to open it in any modern web browser. No `npm install` or local dev server required!

## 💡 Usage

1. **Write Code:** Type standard Mermaid syntax in the left editor panel. The graph will render in real-time.
2. **Customize:** Switch to the `Config` tab to tweak the exact hex colors and shadow intensities of your diagram.
3. **Arrange Visually:** Click the **Ruler/Pen icon** in the bottom left of the preview panel to enter *Visual Edit Mode*. You can now drag nodes and yellow sub-graph boxes around.
4. **Export:** Click "Save Diagram" in the top right to download your work as an SVG.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/shreyas445/Mermaid-Graph-Editor/issues).

## 👨‍💻 Support & Credits

If you find this tool helpful for your system designs, architecture planning, or university projects, Consider leaving a ⭐ on the repository to support the project.

*Released under the [MIT License](LICENSE).
