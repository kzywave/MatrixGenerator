# MatrixGenerator

> Transform logos and images into customizable, retro dot matrix and halftone grid displays.

🌐 **Live Demo:** [https://kzywave.github.io/MatrixGenerator/](https://kzywave.github.io/MatrixGenerator/)

---

## Features

- **Real-Time Matrix Processing**: Upload or paste any image/logo and see it instantly rendered as a dot matrix.
- **Customizable Grid Settings**: Fine-tune column count, dot sizing, spacing, threshold, and contrast.
- **Multiple Visual Styles**: Circle, square, rounded dots, and customizable dot colors and backgrounds.
- **Interactive Pull / Animation Demo**: Test dynamic pull gestures and preview the **transitions.dev Matrix Dot Loader** with 4 motion patterns (`pulse`, `scan`, `orbit`, `twinkle`) and configurable cycle tokens.
- **Export Options**: Export your generated matrix graphics as **SVG**, high-res **PNG**, structured **JSON**, or copy **CSS & React code snippets** compatible with [transitions.dev](https://transitions.dev/detail.html?t=matrix-dot-loader).
- **Zero Dependencies**: Self-contained client-side application running natively in modern web browsers.

---

## Local Development

Simply open `index.html` in any modern web browser or serve it using a local static server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js npx
npx serve
```

Then visit `http://localhost:8000` in your browser.

---

## Deployment

This site is automatically deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the `main` branch.
