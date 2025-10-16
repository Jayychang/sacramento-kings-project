# Sacramento Kings - International Player Targeting (Take-Home)

This repository contains my submission for the **Sacramento Kings Associate Data Scientist (Basketball Operations)** take-home project.

---

This project focuses on identifying high-value international basketball prospects who could strengthen the Sacramento Kings roster, with a particular emphasis on two-way player impact. Leveraging mock performance data from major European leagues (EuroLeague, EuroCup, ACB, and Serie A) and the NBA, I built an end-to-end data science pipeline—from data ingestion, cleaning, and feature engineering to exploratory analysis, modeling, and final ranking.

The analysis began with rigorous data processing and cleaning: standardization, missing value diagnostics, unit normalization, detection of outliers, creation of derived metrics such as per-game statistics and shooting efficiency, and merging. Exploratory Data Analysis (EDA) was used to compare international vs. NBA player distributions, uncovering key structural differences: international players tend to be more role-concentrated, while NBA players exhibit a broader spread at the top of performance metrics.

A composite score was then developed using standardized and weighted features, prioritizing efficient scoring, defensive activity (steals, blocks, BPM), and all-around impact. This scoring system allowed for the creation of a ranked Top 25 Prospect List, highlighting players who stand out as versatile, NBA-ready contributors capable of addressing the Kings’ defensive weaknesses without compromising offensive value.

The final deliverable includes a clean, ranked scouting table with key metrics, percentile visualizations, and distribution analyses that provide actionable insight for player targeting.

---

## Project Structure

### Explanation of folders:
- **`data/`** → Raw JSON files provided.  
- **`notebooks/`** → Jupyter Notebook with the full analysis, from data processing to player ranking.  
- **`reports/`** → Exported HTML report with executive summary, charts, and final player shortlist.  
- **`portfolio/`** → Other relevant projects and case studies.  
- **`requirements.txt`** → Python dependencies required to run the notebook.  
- **`README.md`** → This file — documentation and setup instructions.

---

## How to Reproduce the Analysis

Follow these steps to reproduce the analysis on your local machine:

1. Clone the repository

git clone https://github.com/Jayychang/sacramento-kings-project.git
cd sacramento-kings-project

2. (Optional) Create and activate a virtual environment

python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

3. Install dependencies

pip install -r requirements.txt

4. Launch Jupyter Notebook

jupyter notebook notebooks/sac_kings_notebook.ipynb

5. Run all cells to reproduce the results

## Tech Stack 
- Language: Python
- Libraries: pandas, numpy, matplotlib, scikit-learn
- Environment: Jupyter Notebook
- Report Format: HTML (nbconvert export)
