# ml-zoomcamp-2026-homeworks

My homework solutions for the [Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp) 2026 cohort by DataTalks.Club.

## Structure

Each module has its own folder with `notes/` (lecture notes) and `solutions/` (homework notebook and dataset):

| Module | Topic | Notes | Solution |
|--------|-------|-------|----------|
| 01 | Introduction to Machine Learning | [notes](01-intro/notes/ML_Zoomcamp_01_Intro_Notes.pdf) | [homework.ipynb](01-intro/solutions/homework.ipynb) |
| 02 | Machine Learning for Regression | [notes](02-regression/notes/ML_Zoomcamp_02_Regression_Notes.pdf) | [homework.ipynb](02-regression/solutions/homework.ipynb) |
| 03 | Machine Learning for Classification | [notes](03-classification/notes/ML_Zoomcamp_03_Classification_Notes.pdf) | [homework.ipynb](03-classification/solutions/homework.ipynb) |

## Running the notebooks

Dependencies are managed with [uv](https://docs.astral.sh/uv/) (Python 3.12, pinned in `.python-version`):

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh   # install uv, if needed
uv sync                                           # create .venv from uv.lock
uv run jupyter notebook
uv run jupyter notebook
```

In VS Code, select `.venv/bin/python` as the notebook kernel.
