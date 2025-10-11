# Sacramento Kings - International Player Targeting (Take-Home)

This repository contains my submission for the **Sacramento Kings Associate Data Scientist (Basketball Operations)** take-home project.  

The goal of this exercise is to use international basketball performance data to **identify and prioritize potential player targets** for the Kings’ scouting staff.  
The analysis focuses on data cleaning, exploratory analysis, translating international performance to an NBA context, and communicating clear insights through a professional, reproducible workflow.

--

## Project Structure
sacramento-kings--project/
├─ data/ 
│ ├─ player.json
│ ├─ nba_box_player_season.json
│ └─ international_box_player_season.json
│
├─ notebooks/ 
│ └─ NOTEBOOK NAME
│
├─ reports/ 
│ └─ kings_shortlist.html
│
├─ portfolio/ 
│
├─ requirements.txt 
└─ README.md 

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
jupyter notebook notebooks/NOTEBOOKNAME.ipynb

5. Run all cells to reproduce the results

## Tech Stack 
- Language: Python
- Libraries: pandas, numpy, matplotlib, scikit-learn
- Environment: Jupyter Notebook
- Report Format: HTML (nbconvert export)
