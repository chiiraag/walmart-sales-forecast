# Walmart Sales Forecast

Time-series sales analysis and forecasting for Walmart using Python and ML techniques.

## What's inside
- `notebooks/` — Jupyter notebook for EDA & modeling
- `app/dashboard.py` — Streamlit app (interactive dashboard)
- `data/sample_walmart_sales.csv` — sample schema
- `requirements.txt` — dependencies
- `.gitignore` — common ignores

## Run locally
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
pip install -r requirements.txt

# Notebook
jupyter notebook notebooks/capstone_project_walmart.ipynb

# Streamlit
streamlit run app/dashboard.py
```
