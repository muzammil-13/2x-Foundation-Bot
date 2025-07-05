# 🧠 2x Foundation Bot – Web App

**Tagline:**  
*Double your skills: Learn math, code it, apply it—every day.*

---

## 🔥 Vision

A daily interactive web app empowering students, developers, and lifelong learners to master one math concept per day through:

- Clear explanations  
- Hands-on problem-solving  
- Practical code implementation  

By blending math and coding with real-world applications, 2x Foundation Bot makes learning engaging, approachable, and rewarding.

---

## 🎯 Target Audience

- **Students:** High school/college learners prepping for STEM exams or coding interviews.
- **Developers:** Early-career programmers brushing up on math for algorithms or data science.
- **Hobbyists:** Curious minds seeking a daily brain workout with practical applications.

---

## 🧱 Tech Stack

| Layer         | Technology                                   | Notes                                            |
|---------------|----------------------------------------------|--------------------------------------------------|
| Frontend      | React.js, Tailwind CSS                       | Modern, responsive UI                            |
| Backend       | FastAPI                                      | Async, scalable API for serving challenges       |
| Storage       | JSON (MVP content), SQLite (user data)       | LocalStorage for streak tracking                 |
| Code Execution| Text submission + pre-defined test cases     | Judge0 planned for future auto-run               |
| Deployment    | Netlify (frontend), Railway (backend)        | Rapid, reliable launch                           |
| Future        | Firebase Auth, Caching                       | For scalability and user accounts                |

---

## 🚀 Core MVP Features

| Feature         | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| **🧠 Concept Brief**   | Daily math concept explained simply, with real-world use case.         |
| **🧮 Math Solver**     | 1–2 interactive math questions (MCQ or text input, auto-checked).      |
| **👨‍💻 Code Task**      | 1 code prompt tied to the concept (validated via test cases).         |
| **✍️ Reflection**      | "What did I learn?" journal, stored in LocalStorage.                  |
| **🔄 New Challenge**   | One-click to load a new daily challenge (random/sequential).           |
| **📊 Streak Tracker**  | Tracks daily progress, shows last 7 days’ completion.                  |
| **📬 Feedback Form**   | Collects user feedback on challenges and UX.                          |

---

## 📈 Monetization Plan

- **Freemium Model:**
  - Free Tier: Daily challenges + basic analytics (streak tracking).
  - Premium Tier (Post-MVP): Advanced topics, difficulty levels, detailed analytics, offline access. [Details](https://x.ai/grok)
- **Future:** Community challenge submissions, exclusive content subscriptions.

---

## 🧩 Phase 1: Development Plan (MVP – 12 Days)

| Day | Task                                                                                   |
|-----|----------------------------------------------------------------------------------------|
| 1   | Create JSON-based Concept + Challenge Dataset (10 entries).                            |
| 2   | Set up FastAPI backend to serve random challenges via API.                             |
| 3   | Build React frontend layout (Concept, Math Q, Code Task, Journal).                     |
| 4   | Implement Math Solver (MCQ/text input with validation).                                |
| 5   | Add code submission box (validate via test cases).                                     |
| 6   | Integrate backend API with frontend.                                                   |
| 7   | Build streak tracker (LocalStorage) and feedback form.                                 |
| 8   | Add error handling (invalid input, API failures).                                      |
| 9   | Polish UI, ensure mobile responsiveness.                                               |
| 10  | Beta test with 5–10 users (recruit via X/Discord).                                     |
| 11  | Iterate based on feedback (UX, challenge difficulty).                                  |
| 12  | Deploy via Netlify (frontend) + Railway (backend).                                     |

---

## 📦 Getting Started: `concepts.json` Format

Start with a JSON file containing 10+ high-quality challenges:

```json
[
  {
    "day": 1,
    "concept": "Ratios",
    "explanation": "Ratios compare quantities, used in pricing, design, and recipes.",
    "math_q": {
      "question": "If A:B = 3:2 and total = 25, what are A and B?",
      "type": "text",
      "answer": {"A": 15, "B": 10}
    },
    "code_q": {
      "prompt": "Write a Python function that takes (a:b ratio, total) and returns A and B values.",
      "test_cases": [
        {"input": {"ratio_a": 3, "ratio_b": 2, "total": 25}, "output": [15, 10]}
      ]
    },
    "real_world": "Scaling UI components proportionally in web design.",
    "reflection_prompt": "Where have you seen ratios in your daily life?"
  }
  // ... Add more challenges
]
```

---

## 🌟 Post-MVP Roadmap

- **Phase 2 (1–3 Months):**
  - Expand dataset to 50+ challenges
  - Add difficulty levels (beginner, intermediate, advanced)
  - Gamification (badges, leaderboards)
  - Community challenge submissions (admin dashboard)
- **Phase 3 (3–6 Months):**
  - Adaptive learning (adjusts to user performance)
  - Firebase Auth for user accounts/cloud syncing
  - Premium features (advanced analytics, exclusive content)

---

## 🛠️ Launch Strategy

- **Soft Launch:** Release MVP on Netlify/Railway, target X (#LearnMath, #Coding, #EdTech) and Discord.
- **Marketing:** Share demo video/screenshots on X, Reddit (r/learnprogramming), Discord STEM groups.
- **Feedback Loop:** Use in-app feedback form to iterate quickly.
- **Differentiation:** “Daily brain workout” combining math, coding, real-world application.

---

## ✅ Next Steps

- [ ] Create `concepts.json` with 10 challenges (Day 1)
- [ ] Set up FastAPI backend and test API endpoints (Day 2)
- [ ] Share progress on X to recruit beta testers (Day 10)

---

## 📬 Inspiration

For more, or to subscribe, visit [x.ai/grok](https://x.ai/grok).  
Let’s build a smarter future, one concept at a time!

---

**Frontend:** [React Documentation](https://reactjs.org/docs/getting-started.html)  
**Backend:** [FastAPI Documentation](https://fastapi.tiangolo.com/)  
**UI:** [Tailwind CSS Docs](https://tailwindcss.com/docs/installation)
