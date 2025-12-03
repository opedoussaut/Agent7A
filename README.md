# 🎯 Agent7A  
### *Your personalized climbing training assistant for the Road to 7A*

Agent7A is an adaptive climbing training agent designed to help you reach your next grade with structured planning, session recommendations, block validation, and long‑term progression tracking.

Whether you’re training at the gym, at home, or outdoors, Agent7A generates tailored sessions based on your tools, logs your performance metrics, and keeps you on track toward your objectives.

---

## 🧩 Key Features

- 🧗 **Adaptive training session generator**  
  Generates gym or home sessions based on equipment, current level, and training focus.

- 📝 **Detailed session logging**  
  Track duration, number of boulders, hardest grade, volume, RPE, and notes.

- 🧪 **Block validation with Base Tests**  
  Validate each training block (Base 1, Base 2, Power, Peak) with performance benchmarks.

- 📊 **Progress monitoring**  
  View your progress against planned sessions, block completion, and grade milestones.

- 💬 **Interactive Gradio chat interface**  
  Ask for sessions, log training data, and get status updates directly in chat.

- 📓 **Jupyter Notebook prototype**  
  A testing sandbox to refine the agent logic before deploying the Gradio app.

---

## 📁 Project Structure

```
agent7a/
    core/
        models.py          # Training data models
        planner.py         # Session generation
        analytics.py       # Progress tracking & block evaluation
    ui/
        gradio_app.py      # Main Gradio app
        notebook_prototype.ipynb
    data/
        history/           # Training logs (CSV/JSON)
requirements.txt
README.md
.gitignore
```

---

## 🚀 Getting Started

### 1. Create your virtual environment

#### macOS / Linux:
```
python3 -m venv venv
source venv/bin/activate
```

#### Windows:
```
python -m venv venv
venv\Scripts\activate
```

### 2. Install dependencies
```
pip install -r requirements.txt
```

### 3. Launch the Gradio app
```
python agent7a/ui/gradio_app.py
```

---

## 📓 Notebook Prototype

Start Jupyter Notebook:

```
jupyter notebook
```

Open:

```
agent7a/ui/notebook_prototype.ipynb
```

---

## 📈 Roadmap

| Feature | Status | Notes |
|--------|--------|-------|
| Multi‑climber profiles | ⏳ Planned | e.g., "David – Road to 8A" |
| Block configuration UI | ⏳ Planned | Customize Base/Power/Peak phases |
| Load management analytics | ⏳ Planned | Volume, intensity, fatigue metrics |
| SQLite persistence | ⏳ Planned | Structured, reliable storage |
| Grade prediction curves | ⏳ Planned | Based on performance evolution |

---

## 📜 License

MIT License (or another license of your choice).

---

## 🤝 Contributions

Pull requests and feature suggestions are welcome.

If this project helps your climbing, consider starring the repository!
