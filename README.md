# ⚙️ AI Circuit Optimizer

**AI Circuit Optimizer** is a hybrid C++ + Python system that simplifies and optimizes digital logic circuits using both symbolic logic and machine learning.  
It can analyze messy circuit diagrams, convert them into Boolean expressions, and automatically rebuild the most efficient version using only available components (e.g., NAND, NOR, MUX, or Decoder structures).

---

## 🧠 Motivation

In digital circuit design, engineers often need to:
- Simplify complex logic circuits
- Convert between gate forms (AND/OR/NOT → NAND/NOR)
- Reimplement using multiplexers or decoders  
These tasks quickly become tedious for large designs.  

**AI Circuit Optimizer** learns and automates this process — enabling intelligent circuit restructuring with both **classical Boolean simplification** and **AI-driven optimization**.

---

## 🚀 Features

- 🧩 Parse logic gate diagrams from images (OpenCV-based)
- 🧮 Convert circuits into symbolic Boolean equations
- ⚡ Simplify logic with **Quine–McCluskey**, **Espresso**, or **Sympy**
- 🔁 Convert to **NAND/NOR/MUX/Decoder-only** implementations
- 🧠 Use ML to predict efficient gate arrangements
- 🧰 Built with **C++ core engine** + **Python ML layer**
- 🌐 Optional web UI for visual input/output (React + FastAPI backend)

---

## 🧱 Tech Stack

|       Layer       |    Technology    |            Purpose            |
|-------------------|------------------|-------------------------------|
|  **Core Engine**  | C++17 + PyBind11 | Fast Boolean simplification and gate conversion |
|   **AI Engine**   |      PyTorch     | Learns optimization heuristics from circuit datasets |
| **Image Parser**  | OpenCV + Python  | Detects gates, wires, and inputs from diagram images |
| **Logic Engine**  | Sympy | Symbolic Boolean manipulation |
|  **Web Backend**  | FastAPI | RESTful API for circuit analysis and simplification |
|    **Frontend**   | NextJS + TypeScript + Canvas/SVG | Draw or upload circuit diagrams |
| **Visualization** | NetworkX + Matplotlib | Graph output for simplified circuits |

---

## 🗺️ Project Architecture

TBD
