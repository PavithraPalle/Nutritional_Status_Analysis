# 🧒 Nutritional Status Analysis in Telangana

This project analyzes child malnutrition data across districts, sectors, and Anganwadi centers using PySpark and interactive visualizations.

## 📊 Key Features

- District-wise trends in underweight, stunting, and wasting
- Interactive Plotly charts with drill-down capabilities
- Correlation heatmaps between malnutrition indicators
- Cleaned dataset with focused metrics

## 📁 Dataset

- Source: `data/dataset.csv`
- Columns used:
  - `Reporting Month`
  - `D_Name` (District)
  - `Sec_NAme` (Sector)
  - `AWc_Name` (Anganwadi Center)
  - `Tot_UW_Normal`, `Tot_Wasting_Normal`, `Tot_Stunting_Normal`

## 📈 Visualizations

- Bar chart: District-wise stunting levels
- Line chart: Underweight trends over time
- Sunburst: Drill-down from district → sector → AWC
- Heatmap: Correlation between malnutrition metrics

## 🛠️ Tech Stack

- Python 3.10+
- PySpark
- Pandas
- Matplotlib & Seaborn
- Plotly

## 🚀 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run analysis
python analysis.py
```
