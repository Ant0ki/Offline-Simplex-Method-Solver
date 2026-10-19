# 📊 Simplex Method Solver for Android

An open-source, lightweight, offline-first Android application to solve **Linear Programming (LP)** problems using the **Simplex Method** and **Two-Phase Simplex Method**.

Designed for students, educators, and operations research practitioners, this app provides detailed step-by-step tableau calculations, exact fraction conversions, and interactive 2D graphical visualizations of the feasible region.

---

## ✨ Features

- **Objective Optimization**: Supports both **Maximization** and **Minimization** problems.
- **Flexible Matrix Inputs**: Dynamically add or remove decision variables ($X_1, X_2, \dots, X_n$) and constraint equations ($C_1, C_2, \dots, C_m$).
- **Full Constraint Support**: Handles `<=`, `>=`, and `=` operators seamlessly using Slack, Surplus, and Artificial variables via the **Two-Phase Simplex Method**.
- **Step-by-Step Simplex Tables**: Displays complete iteration tableaux including $C_j$, $Z_j$, $C_j - Z_j$, entering/leaving basis indicators, ratios, and highlighted pivot elements.
- **Graphical Feasible Region Plot**:
  - 2D Polygon visualization of the feasible region for 2-variable LP problems.
  - Plots constraint boundary lines, vertices, and highlights the optimal solution ($\star$).
  - Graphs objective function ($Z$) value progression across iterations.
- **Exact Fraction Formatting**: Outputs numbers as fractions (e.g., $1/3$, $5/2$) or decimals for clean readability.
- **100% Offline & Private**: All calculations run locally on the device; zero data collection or network calls required.

---

## 🛠 Tech Stack & Architecture

- **Platform**: Android Native (Java)
- **Container**: Native `WebView` wrapper (`MainActivity.java`)
- **Engine / UI**: Lightweight single-page web app built with Vanilla JavaScript, HTML5, and CSS3 SVG graphics (`index.html`)
- **Compatibility**: Android 5.0 (Lollipop, API 21) and above

---

## 🚀 Getting Started

### Building from Source

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/simplex-solver.git
