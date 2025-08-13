# Diwali_Sales_Analysis

# Diwali Sales Analysis

A compact, reproducible analysis of seasonal purchasing patterns using a Diwali retail dataset. The notebook explores customer demographics, product categories, and order value trends to surface actionable insights for marketing and inventory planning.

## 📦 Repository structure

```
diwali-sales-analysis/
├─ Diwali_Sales_Analysis.ipynb
├─ data/
│  └─ Diwali Sales Data.csv
├─ requirements.txt
└─ README.md
```

> Tip: keep the raw dataset in `data/`. If the file is large or sensitive, consider storing it outside Git or using Git LFS.

## 🚀 Quickstart

### 1) Clone and enter the project
```bash
git clone <your-repo-url>.git
cd diwali-sales-analysis
```

### 2) Create a virtual environment
**Windows (PowerShell):**
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**macOS / Linux (bash/zsh):**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3) Install dependencies
```bash
pip install -r requirements.txt
```

### 4) Launch Jupyter and open the notebook
```bash
jupyter notebook
```
Open `Diwali_Sales_Analysis.ipynb` to run the analysis.

## 🗂️ Data
- **File:** `data/Diwali Sales Data.csv`

**Available columns:**
_(Columns will be listed once the dataset is in the repository.)_

> If your dataset differs, update this section accordingly.

## 📊 What the notebook covers
- Data cleaning and type fixes for analysis-ready tables
- Exploratory analysis: sales by gender, age group, state/city, and occupation
- Product/category performance and top contributing items
- Order value distribution and revenue contribution
- Simple, presentation-ready charts (Matplotlib/Seaborn)

## 🧪 Reproducibility
- The notebook is self-contained and uses only the libraries listed in `requirements.txt`.
- Set the working directory to the project root (where `README.md` lives) before running.

## ✅ Results (highlights to fill in)
- Example: *Women contributed ~X% of revenue, with highest average order value from the 26–35 age group.*
- Example: *Top categories: Electronics and Clothing, contributing ~Y% of total sales.*
- Example: *North region led revenue; targeted campaigns during festive weeks improved conversion.*

> Replace the above with your findings once you run the analysis.

## 🗺️ Roadmap / Next steps
- Build an interactive dashboard (Streamlit/Plotly) for filters and drill-downs
- Add cohort analysis or simple RFM segmentation
- Automate weekly data refresh and reporting

## 🤝 Contributing
PRs are welcome. Please open an issue to discuss major changes.

## 📜 License
Choose a license (e.g., MIT) or remove this section.
