# Python Time-Series & Forecasting Practice

An educational project exploring COVID-19 time-series data with **Pandas, Plotly, Matplotlib, and Prophet**.

This repository currently contains one forecasting project, provided as a notebook and an exported Python script.

## What's included

| File | Purpose |
| --- | --- |
| [covid19_prediction_.ipynb](./covid19_prediction_.ipynb) | Main notebook for data exploration, visualization, and forecasting |
| [covid19_prediction_.py](./covid19_prediction_.py) | Python export of the notebook workflow |

The workflow includes country-level aggregation, geographic visualizations, rolling averages, and a 30-day Prophet forecast.

## Explore the notebook

The notebook expects these CSV files, which are **not included in this repository**:

- `CONVENIENT_global_confirmed_cases.csv`
- `CONVENIENT_global_deaths.csv`
- `continents2.csv`

Provide compatible data files in the notebook's working directory and check the expected columns before running it.

A local Python environment needs Jupyter, NumPy, Pandas, Matplotlib, Plotly, Prophet, and scikit-learn:

```bash
python -m venv .venv
# Activate the environment for your operating system, then:
python -m pip install jupyter numpy pandas matplotlib plotly prophet scikit-learn
jupyter notebook covid19_prediction_.ipynb
```

## Learning focus

- Cleaning and aggregating time-series data.
- Comparing trends through interactive visualizations.
- Preparing date/value columns for Prophet.
- Understanding the limits of forecast evaluation.

## Limitations

This is a learning exercise, not a validated forecasting service. The R² calculation in the exported workflow uses training data; it is not an independent measure of future forecast performance. Data compatibility and a full clean-environment run still need to be verified.

Use the notebook as the primary walkthrough. The Python file is an exploratory export and may need cleanup before standalone execution.

---

Created by [Azeem Ahmad](https://github.com/AzeemAhmad123). See my [portfolio](https://portfolio-gamma-lake-28.vercel.app/) for current computer vision and full-stack work.

