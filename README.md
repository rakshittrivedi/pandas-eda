# Pandas EDA Portfolio
> Three end-to-end data analysis projects built during a structured
> Python + Pandas learning sprint. Each project follows a real-world
> analyst workflow: ingest → clean → analyse → insight → export.

## Projects

### 1. Bollywood Box Office Autopsy
**File:** `notebooks/01_bollywood_box_office.ipynb`
**Dataset:** [Bollywood Movies — Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
**Question:** What actually drives box office ROI?

**Key Findings:**
- Budget and collection have only [X] correlation —
  story and timing matter more than spend
- Mid-budget films (₹30–60Cr) outperform mega-budget
  films on ROI consistently
- [Month] releases generate [X]% higher average ROI —
  holiday windows dominate

**Skills:** `pd.read_csv` `str cleaning` `pd.cut` `groupby.agg`
`correlation` `lambda` `apply`

---

### 2. India Air Quality Time Bomb
**File:** `notebooks/02_india_air_quality.ipynb`
**Dataset:** [Air Quality Data in India — Kaggle](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
**Question:** Which Indian cities face a PM2.5 health crisis,
and is it getting better or worse?

**Key Findings:**
- [Top city] exceeds WHO PM2.5 limit by [X]x annually
- Oct–Jan accounts for [X]% of all critical AQI days
  (stubble burning + winter inversion)
- [X]% of cities show worsening trend in last 3 years

**Skills:** `pd.to_datetime` `city name standardisation`
`pivot_table` `trend analysis` `policy writing`

---

### 3. Employee Churn Early Warning System
**File:** `notebooks/03_employee_churn.ipynb`
**Dataset:** [IBM HR Analytics — Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
**Question:** Which employee segments are most at risk
of leaving, and why?

**Key Findings:**
- [Department] has [X]% attrition vs [Y]% company average
- Employees aged 18–25 leave at [X]x the company rate
- Overtime multiplies attrition risk by [X]x regardless
  of salary band

**Skills:** `groupby` `multi-dimension cross-analysis`
`pd.cut` `apply` `executive summary writing`

---

## How to Run
```bash
git clone https://github.com/[username]/pandas-eda
cd pandas-eda

# Install dependencies
pip install pandas numpy jupyter

# Launch
jupyter notebook notebooks/
```

**Data setup:** Download datasets from the links above and place
CSVs in the `data/` folder before running notebooks.

## Skills Demonstrated
`Data Cleaning` `Null Handling` `Feature Engineering`
`GroupBy Analysis` `Merge/Join` `Outlier Detection`
`Business Insight Writing` `Executive Communication`
