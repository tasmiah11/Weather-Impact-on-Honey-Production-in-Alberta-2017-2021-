# 🐝 Weather Impact on Honey Production in Alberta (2017–2021)
This project investigates how weather patterns affect honey production in Alberta, Canada. Using Python and Jupyter Notebook (honey_bee.ipynb) for data analysis and a detailed research writeup (Weather Impact on Honey Production in Alberta.docx), the study explores correlations between weather metrics and honey yield at various bee life stages.


---

## 📦 Files

- `honey_bee.ipynb`: Full Python notebook for data cleaning, feature engineering, and analysis
- `Weather Impact on Honey Production in Alberta.docx`: Research write-up
- `honey_bee.html`: Rendered notebook for non-technical review
- `teamwork.html`: Likely a supporting collaboration file or team report

---

## ✅ Key Activities

### 1. Data Cleaning & Feature Engineering
- Cleaned 5 years of weather data
- Created bee-relevant metrics: temperature deviation, days near optimal, etc.

### 2. Trend Analysis
- Visualized:
  - Monthly average temperatures
  - Humidity and solar radiation trends
  - Wind and precipitation patterns

### 3. Correlation & Interpretation
- Yearly-level and stage-wise correlation with honey yield
- Strongest predictors:
  - **+0.65**: `AvgTemp_Pupa`
  - **+0.63**: `Humidity_Larva`
  - **–0.76**: `SolarRad_Larva`

### 4. Stage-Specific Insight
- 🐣 Larva: Sensitive to humidity and solar stress
- 🐝 Pupa: Most influential—moderate weather boosts production
- 🌼 Adult: Less correlation found

---

## 💡 Key Insights

- Annual averages are misleading. Life-stage-specific data gives more accurate signals.
- Beekeeping strategies should prioritize thermal and moisture control during spring.

---

## 🧰 Tools

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Microsoft Word for report documentation

---

## 📈 Outcome

A well-supported recommendation for beekeepers and agricultural analysts: **focus on maintaining optimal conditions during larval and pupal stages to maximize honey yield**.

---
