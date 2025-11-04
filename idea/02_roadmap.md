# Development Roadmap — AI Circuit Optimizer

## Phase 2 — Circuit Input Handling (Weeks 1–3)

- Use OpenCV to parse gates and wires from input image.
- Build CNN to classify gate types (AND, OR, NOT).
- Convert detected gates and connections into a logic graph using NetworkX.
- Output symbolic Boolean expressions using Sympy.

**Deliverable:** Parser that converts `circuit.png` → Boolean expression.

---

## Phase 3 — Logic Simplification Engine (Weeks 4–6)

- Implement Boolean simplification with Sympy and a custom C++ Quine–McCluskey version.
- Add conversion modules: `to_nand()`, `to_nor()`, `to_mux()`, `to_decoder()`.
- Visualize simplified circuits with NetworkX.

**Deliverable:** CLI or REST API returning simplified and converted logic circuits.

---

## Phase 4 — Intelligent Optimization (Weeks 7–10)

- Generate dataset: random Boolean expressions → simplified outputs.
- Train PyTorch model to predict optimal simplifications or component configurations.
- Integrate ML model into the optimization workflow (hybrid engine).

**Deliverable:** ML-driven optimizer that improves simplification efficiency.

---

## Phase 5 — Frontend Integration (Weeks 11–13)

- Build Next.js web interface for uploading/drawing circuits.
- Connect to FastAPI backend.
- Render output circuit graph and efficiency metrics.

**Deliverable:** Interactive web UI with backend connection.

---

## Phase 6 — Final Polish & Portfolio (Weeks 14–15)

- Create demo video and GitHub README.
- Deploy backend (Render/Railway) and frontend (Vercel).
- Write report and add documentation.

**Deliverable:** Fully deployed demo + presentation-ready portfolio project.
