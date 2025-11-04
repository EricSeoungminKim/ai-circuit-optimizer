# Tech Stack Overview — AI Circuit Optimizer

## Languages

- **Python 3.11+** — backend, AI, image parsing
- **C++17** — core Boolean simplification and circuit conversion engine
- **TypeScript** — for frontend (Next.js)
- **HTML/CSS** — UI rendering

## Frameworks and Libraries

### 🧠 AI / ML

- PyTorch — for model training and heuristic learning
- NumPy, Pandas — data handling

### 🔢 Logic Simplification

- Sympy (Python) — symbolic Boolean manipulation
- Custom C++ simplifier — fast Quine–McCluskey / Espresso-style algorithms

### 🧩 Image Parsing

- OpenCV — gate and wire detection
- NetworkX — circuit graph representation

### 🌐 Web Stack

- FastAPI — backend API (Python)
- Next.js — frontend (React + SSR)
- Tailwind CSS — styling
- Framer Motion — animations

### ⚙️ Integration

- PyBind11 — connect C++ logic engine to Python
- REST API — connect FastAPI backend to Next.js frontend
- SQLite — local data persistence

### 💾 Optional Tools

- Logisim Evolution — for dataset generation or verification
- Verilog (optional) — for hardware validation
