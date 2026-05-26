## RTSM Project 

# The Aggregation Paradox: Why Simpler  Seasonal Baselines Defeat Feature-Heavy  Models in Retail Macro-Forecasting

## Professional Summary

This repository contains a course group project for	REGRESSION ANALYSIS AND TIME SERIES MODELS(MA60280) for Spring 2025-26. The work documents a clear, reproducible approach to feature engineering, model selection, and evaluation for retail demand forecasting.

## Highlights

- Cross-functional collaborator: translate business questions into data problems and clear metrics.
- Strong foundation in feature engineering, model validation, and time-series cross-validation.
- Emphasis on reproducibility: notebooks, scripts, and clear data lineage in `datasets/`.

## Technical Skills

- Languages & libs: Python, pandas, NumPy, scikit-learn, LightGBM / XGBoost, PyTorch (as needed)
- Data: feature engineering, missing value strategies, encoding categorical features
- Modeling: regression, tree-based models, ensembles, hyperparameter tuning
- Tools: Jupyter notebooks, Git, Docker, basic ML deployment patterns

## This Repository (What you'll find here)

- Notebooks: `RTSM_Project (1).ipynb` — exploratory analysis, model experiments, and visualizations.
- Scripts: `rtsm_project (1).py` — reproducible data processing and modeling pipeline (script form).
- Data: `datasets/` contains `train.csv`, `features.csv`, and `stores.csv` used for training and analysis.

## Project Summary — Retail Time-Series Modeling (MA60280)

Goal: forecast demand/sales across stores using historical sales and engineered features. This project was completed as part of the MA60280 course (Spring 2025-26) and demonstrates best-practice workflows for regression and time-series modeling.

Approach:

- Inspect data and missingness; construct interpretable features from `features.csv` and `stores.csv`.
- Apply time-aware cross-validation with lag and rolling-window features to prevent leakage.
- Benchmark baselines and tree-based ensembles; prioritize models that balance accuracy and interpretability.

Outcome:

The repository includes an exploratory notebook and a reproducible script to run the core pipeline. Experiments and results are documented for clarity and reproducibility so reviewers or instructors can reproduce findings.

## How to run (quick start)

1. Create a virtual environment and install dependencies (example):

```bash
python -m venv .venv
source .venv/bin/activate
pip install -U pip
# Install libraries commonly used in the notebooks
pip install pandas numpy scikit-learn jupyter matplotlib seaborn lightgbm
```

2. Open the notebook `RTSM_Project (1).ipynb` to reproduce the exploratory analysis and model experiments.

3. Run the lightweight pipeline script for a reproducible run:

```bash
python "rtsm_project (1).py"
```

Notes:
- If you plan to run heavy training, consider adding a `requirements.txt` or `environment.yml` tailored to your environment.
- For production or deployment, containerize the environment with Docker and pin dependency versions.

## Video Presentation

Watch the project walkthrough here: [Video Presentation](https://drive.google.com/file/d/1WP-Dl0NIHodLJq1HFaHlvrYrW53n4l0H/view?usp=sharing)

## Contact

If you'd like collaboration or feedback, reach out: your.name@example.com — happy to walk through the experiments and decision points.

---

Created to give maintainers and reviewers a human, professional overview of the repository and modelling intent.
