# Image Transition (Before/After Slider)

An interactive, responsive split-screen image slider that allows users to seamlessly compare two images using a draggable handle. This project is ideal for showcasing photo edits, design overhauls or before/after visual comparisons.

## ✨ Features

* **Interactive Draggable Slider:** Smooth control handle allowing users to reveal or hide the background image in real-time.
* **Seamless Visual Split:** Uses pixel-precise clipping/width adjustments for a perfectly synced comparison.
* **Fully Responsive:** Designed to look great and scale perfectly across desktops, tablets and mobile viewports.
* **Modern UI:** Clean, minimalist interface focusing entirely on the visual presentation.

## 🛠️ Built With

* **HTML5:** Semantic structure for the slider container and handle elements.
* **CSS3:** Custom layout design, styling for the slider track/handle and handling initial positioning.
* **Vanilla JavaScript:** Event-driven logic capturing mouse movement (`mousemove`) to dynamically calculate the split position.

## 📦 Getting Started

### Prerequisites

All you need is a modern web browser (Chrome, Edge, Firefox, Safari) to run the project.

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Bineth-Tharana/Image-Transition.git](https://github.com/Bineth-Tharana/Image-Transition.git)

```

2. **Navigate into the folder:**
```bash
cd Image-Transition

```


3. **Launch the project:**
Simply double-click the `index.html` file to open it instantly in your browser or open the folder in VS Code and use the **Live Server** extension.

## 📂 Project Structure

```text
Image-Transition/
├── index.html       # Main structure and JavaScript logic
├── style.css        # Layout structure, absolute positioning and handle styling
└── README.md        # Project documentation

```

## ⚙️ How It Works

The slider functions by stacking two images directly on top of each other using CSS absolute positioning. The top layer's width is controlled dynamically by JavaScript based on the X-coordinate position of the slider handle. As the user drags the mouse, the width of the foreground element updates instantly, revealing the image underneath.

## 👤 Author

* **Bineth Tharana** - [GitHub Profile](https://www.google.com/search?q=[https://github.com/Bineth-Tharana](https://github.com/Bineth-Tharana))

```
