# Aura Graph Plotter



**Aura Graph Plotter** is a powerful, interactive, and beautifully designed web-based application for visualizing mathematical functions. It supports both Cartesian (y = f(x)) and Polar (r = f(t)) plots and includes advanced analysis tools, all wrapped in a sleek, modern, and responsive user interface.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://en.wikipedia.org/wiki/HTML5)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com)

---

## ✨ Key Features

-   **Dual Plotting Modes:**
    -   **Cartesian:** Plot functions in the form `y = f(x)`.
    -   **Polar:** Plot functions in the form `r = f(t)`, where `t` is the angle (theta).

-   **Fully Interactive Chart:**
    -   **Zoom:** Use the mouse wheel or pinch-to-zoom.
    -   **Pan:** Click and drag the chart to explore.
    -   **Reset:** Double-click the chart to reset view.
    -   **Crosshair:** Hover to see precise coordinates on the graph.

-   **Advanced Analysis (Cartesian Plots):**
    -   **Derivative Plotting:** Automatically calculate and plot the first derivative `f'(x)`.
    -   **Integral Plotting:** Symbolically calculate and plot the integral `∫f(x)dx`.
    -   **Full Analysis:** Instantly find:
        -   **Roots:** Points where the function crosses the x-axis.
        -   **Extrema:** Local minimums and maximums.
        -   **Area:** Definite integral (area under the curve) within the specified range.

-   **Modern User Experience:**
    -   **"Aura" Theme:** A stunning dark theme with glassmorphism, gradient borders, and fluid animations.
    -   **Responsive Design:** Flawless performance on desktops, tablets, and mobile devices.
    -   **Function History:** A dropdown saves your recent equations for quick re-plotting.

-   **Utilities & Performance:**
    -   **PNG Export:** Export your graph as a high-quality PNG, complete with a title, legend, and analysis results summary.
    -   **Grid Toggle:** Show or hide the chart's grid lines.
    -   **Help Guide:** An integrated, easy-to-read help modal.
    -   **Efficient Engine:** Uses `Math.js` for robust parsing and symbolic math, with expression caching to speed up re-renders.

## 🚀 How to Use

1.  **Select Plot Type:** Choose between `Cartesian` or `Polar`.
2.  **Enter Your Function:**
    -   For **Cartesian**, use `x` as the variable (e.g., `sin(x^2) / x`).
    -   For **Polar**, use `t` as the variable (e.g., `1 + 2*cos(t)`).
3.  **Adjust Range (Optional):** Set the min/max values and the step/precision for the plot.
4.  **Plot!** Press the **"Plot Graph"** button or hit `Enter`.
5.  **Analyze:** Use the `f'(x)`, `∫f(x)dx`, and `Analyze` buttons to explore the function's properties (Cartesian mode only).

### Supported Expressions

Thanks to **Math.js**, a wide range of mathematical expressions are supported:
-   **Operators:** `+`, `-`, `*`, `/`, `^` (power)
-   **Functions:** `sin()`, `cos()`, `tan()`, `log()`, `sqrt()`, `abs()`, and many more.
-   **Constants:** `pi`, `e`.
-   **Custom Functions:** `cot()`, `sec()`, `csc()` are also supported.

## 🛠️ Technologies Used

-   **Core:** HTML5, CSS3, JavaScript (ES6+)
-   **Styling:** [Tailwind CSS](https://tailwindcss.com/) & Custom CSS for animations and theme.
-   **Charting:** [Chart.js v4](https://www.chartjs.org/)
-   **Chart Plugins:**
    -   `chartjs-plugin-zoom` for panning and zooming.
    -   `chartjs-plugin-crosshair` for the hover-line.
-   **Math Engine:** [Math.js](https://mathjs.org/) for expression parsing, evaluation, and symbolic differentiation/integration.

## 🖥️ Local Setup

No complex setup required! This is a self-contained single-file application.

1.  Clone the repository or download the `index.html` file.
2.  Open the `index.html` file in any modern web browser (like Chrome, Firefox, or Edge).

That's it! The application will run locally.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
