## 🧠 Vision: “2x Foundation Bot – Web App”

### 🔥 Goal:

> A daily *interactive system* that helps you learn **one math concept per day**, apply it via **problem-solving**, and reinforce it via **code implementation**.

---

## 🧱 Tech Stack (Confirmed)

* **Frontend:** React.js + Tailwind (UI)
* **Backend:** Python (Flask or FastAPI)
* **Storage:** JSON or SQLite (for MVP), can scale later
* **Bonus Later:** LocalStorage or Firebase Auth for streak tracking

---

## 🎯 Core MVP Features

| Feature               | Description                                                               |
| --------------------- | ------------------------------------------------------------------------- |
| 🧠 **Concept Brief**  | Daily explanation of a math concept in simple terms + real-world use case |
| 🧮 **Math Solver**    | 1–2 interactive math questions (auto-check answers or free input)         |
| 👨‍💻 **Code Task**   | 1 coding prompt linked to the concept (auto-run or submission box)        |
| ✍️ **Reflection**     | "What did I learn?" journal area (store locally)                          |
| 🔄 **New Challenge**  | One-click to load a new day challenge (random or sequential)              |
| 📊 **Streak Tracker** | Track daily progress, show last 7 days completion                         |

---

## 🧩 Phase 1: Development Plan (MVP - 10 Days)

| Day | Task                                                               |
| --- | ------------------------------------------------------------------ |
| 1   | ✅ Create JSON-based **Concept + Challenge Dataset** (5–10 entries) |
| 2   | Setup backend (Flask/FastAPI) API to serve random challenge        |
| 3   | Create React frontend layout (Concept, Math Q, Code Task, Journal) |
| 4   | Implement Math Q interaction (text input or MCQ)                   |
| 5   | Add code editor (Monaco/CodeMirror) + test run area (basic)        |
| 6   | Hook backend with frontend (API)                                   |
| 7   | Build streak tracker (LocalStorage or DB)                          |
| 8   | Add “Submit” and “Next” button logic                               |
| 9   | Polish UI + responsiveness                                         |
| 10  | Deploy via Netlify + Render (or Vercel + Railway)                  |

---

## 📦 Let's Start Today With:

### ✅ Step 1: Create `concepts.json`

We’ll define 5 sample challenges in this format:

```json
[
  {
    "day": 1,
    "concept": "Ratios",
    "explanation": "Ratios are used to compare quantities. Common in prices, design, recipes.",
    "math_q": "If A:B = 3:2 and total = 25, what are A and B?",
    "code_q": "Write a Python function that takes (a:b ratio, total) and returns A and B values.",
    "real_world": "Scaling UI components proportionally.",
    "reflection_prompt": "Where have you seen ratios used in your daily life?"
  },
  ...
]
```

---
