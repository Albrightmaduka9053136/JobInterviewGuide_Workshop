# JobInterviewGuide_Workshop

This repository contains a Jupyter Notebook `JobInterviewGuide_Workshop.ipynb` created to prepare for a junior Machine Learning Specialist interview. The notebook includes:

- Full conversation transcript between the user and assistant for the study session.
- Weak-topics deep dives (Parametric vs Non-parametric models, R², Identifying non-parametric models, Logistic regression loss).
- Worked code examples and solved exercises using scikit-learn (regression, classification, model comparison, metrics, ROC, log loss).
- Reflection prompts for the candidate to answer.

Prerequisites
- Python 3.8+ (3.9 or 3.10 recommended)
- pip

Setup (PowerShell)

# Create and activate a venv
python -m venv .venv; .\.venv\Scripts\Activate.ps1

# Upgrade pip and install requirements
python -m pip install --upgrade pip; pip install -r requirements.txt

Running

# Start Jupyter Notebook and open the file
jupyter notebook JobInterviewGuide_Workshop.ipynb

Notes
- The notebook already includes the required imports at the top cell.
- If plots don't display, ensure you are running the notebook in an environment with GUI support or use inline backends.

What's included
- `JobInterviewGuide_Workshop.ipynb` — full workbook with transcript, deep dives, quizzes, code, and reflection.
- `requirements.txt` — pinned dependencies used by the notebook.

Next steps
- Add unit tests for key data-processing functions (if extracted).
- Convert key exercises into parameterized scripts for quick validation.
- Add a shorter "cheat-sheet" markdown for interview-ready answers.
