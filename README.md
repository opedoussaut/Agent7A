Agent7A

Agent7A is a climbing training assistant designed to help athletes reach their goals — starting with the Road to 7A.
It generates training sessions, logs detailed performance metrics, evaluates training blocks, and monitors progression over time.

🚀 Features

Training session generation (gym or home, equipment-aware)

Detailed session logging, including:

Date & duration

Number of boulders

Hardest grade

RPE

Notes

Base-test flag

Block evaluation (Base 1, Base 2, Power, Peak…)

Progress tracking toward your target grade

Interactive Gradio chat agent

Jupyter Notebook prototype for experimentation

Runs entirely inside a virtual environment

📁 Project Structure
agent7a/
    core/
        models.py          # Training data models
        planner.py         # Session generator
        analytics.py       # Progress + base-test evaluation
    ui/
        gradio_app.py      # Main Gradio application
        notebook_prototype.ipynb
    data/
        history/           # Training logs

🧩 Installation

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows


Install dependencies:

pip install -r requirements.txt

▶️ Running the Gradio App
python agent7a/ui/gradio_app.py


This will open the interactive chat interface where you can:

ask for a gym or home session

log a training session

evaluate block progress

check if your base test is validated

📓 Jupyter Notebook Prototype

Launch Jupyter:

jupyter notebook


Open:

agent7a/ui/notebook_prototype.ipynb


This is the recommended way to iterate on the agent logic before using the full Gradio UI.

📈 Roadmap

Multi-climber profiles (e.g., David → Road to 8A)

Configurable training blocks through the UI

Improved load management & analytics

SQLite persistence

Performance-curve modeling for grade prediction

📜 License

MIT license (or another license of your choice).
