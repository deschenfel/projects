# Portfolio — Débora S. G. Baena

Projects covering **data modeling**, **Python**, **SQL**, **pandas**, **NumPy**, **scikit-learn**, **matplotlib**, and **seaborn** — from data wrangling to visualization and predictive models. The goal is to produce **actionable insights** with sound engineering and analytics practices.

## Repository Purpose
Centralize hands-on studies and case work spanning **ingestion/ETL**, **cleaning and modeling**, **exploratory analysis**, **dashboards**, and **machine learning**. Each project folder includes its own README with the scope, data, methodology, and results.

## Tech Stack
- **Language:** Python 3.9+
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn
- **SQL:** relational modeling, CTEs, window functions (e.g., BigQuery/PostgreSQL syntax)
- **ETL & Data:** CSV/Excel ingestion, schema standardization, basic data validation
- **Dashboards (when applicable):** Power BI / Looker Studio / Tableau (familiar)
- **Dev Environment:** Jupyter / VS Code, Git/GitHub, Markdown documentation

## 📁 Suggested Structure
```
.
├── data/                 # samples or mock data (avoid committing sensitive data)
├── notebooks/            # EDA and experiments
├── src/                  # reusable scripts (ETL, features, utils, etc.)
├── reports/              # charts, PDFs, figures
├── requirements.txt
└── <project-X>/          # specific project folder (with its own README)
```
> Note: some projects may adopt their own structure (e.g., a standalone `project-X/` with `data/`, `src/`, `notebooks/`).

## How to Reproduce
1. **Clone:**
   ```bash
   git clone <YOUR_REPO_URL>.git
   cd <REPO_FOLDER>
   ```
2. **(Optional) Create a virtual environment and install dependencies:**
   ```bash
   python -m venv .venv
   # Windows: .venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
3. **Run notebooks or scripts:**
   - Notebooks in `notebooks/` (Jupyter/VS Code)
   - Scripts in `src/` (each project README provides instructions)

## Recurring Topics
- **Data modeling:** normalization, keys/integrity, star schema when useful
- **Advanced SQL:** CTEs, joins, window functions, basic performance tips
- **ETL/ELT:** ingestion, cleaning, type casting, data validation
- **EDA & visualization:** descriptive statistics, plots with matplotlib/seaborn
- **Machine Learning (when applicable):** baselines, train/test split, metrics (accuracy, F1, ROC-AUC), cross-validation
- **Best practices:** version control, clear docstrings, tidy notebooks, reproducibility

## Example Project Types
- **People Analytics — KPIs & Turnover**  
  Dashboards and HR KPIs; data modeling for engagement/attrition; SQL + Power BI.
- **Telecom — Plan Usage & Revenue**  
  Monthly aggregations per user, plan revenue analysis, feature engineering, visualizations.
- **Localization Metrics — ETL & BI**  
  Ingestion pipeline (CSV/Sheets → SQL), schema standardization, summary dashboards.

> Replace or complement the examples above with your actual project folders and descriptions.

## Code & Quality Standards
- **PEP 8** style, type hints where helpful, reusable functions in `src/`
- **Clean notebooks:** short cells, narrative flow, legible charts
- **Documentation:** each project includes a short README (objective → data → approach → results)

## Roadmap
- [+] Consolidate EDA/ETL templates
- [ ] Add basic unit tests for `src/`
- [ ] Publish screenshots or summaries in project READMEs
- [ ] Explore lightweight pipelines with Make or task runners

## License
Distributed under the **MIT License** (or adapt as needed).

---

