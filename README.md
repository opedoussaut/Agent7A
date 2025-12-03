# Agent7A  
**An adaptive climbing training agent built for the Road to 7A.**

Agent7A is a virtual training companion that helps climbers:

- Plan their training (home or gym)
- Log sessions with detailed metrics (grades, volume, RPE, base-test flags)
- Evaluate block completion (Base 1, Base 2, Power, Peak)
- Monitor progression toward a target grade (7A by default)
- Interact via an interactive Gradio chat interface
- Work entirely in a local virtual environment or notebook

---

## 📦 Project Structure

```text
agent7a/
    core/
        models.py        # Training data models
        planner.py       # Generates sessions (home/gym)
        analytics.py     # Progress & base-test evaluation
    ui/
        gradio_app.py    # Main UI app
        notebook_prototype.ipynb
    data/
        history/         # Logged sessions (JSON/CSV)
