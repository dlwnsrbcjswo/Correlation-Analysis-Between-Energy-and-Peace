<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/c500af2f-af90-4ed0-bbc0-196b53d6bdb3" />

# Correlation-Analysis-Between-Energy-and-Peace
Correlation Analysis Between Energy Consumption per Capita and the Positive Peace Index (PPI)

**Short description**
This project explores the relationship between *energy consumption per capita (MMBtu/person)* and various Producer Price Index (PPI) indicators. Analysis includes regional breakdowns, correlation analysis, scatterplots with regression lines, and a short machine-learning experiment.

**Data**
- `energy per capita.xlsx` — energy consumption per capita by country/region (sensitive/large files not included).
- `PPI data.xlsx` — PPI time series / aggregated indicators.
> **Note:** Raw data is not included in this repo (see `data/README.md` for download instructions). Do not push confidential data.

**Key results (draft)**
- Project focus: correlation patterns between energy consumption per capita and multiple PPI features across regions.
- Example (fill with your final insights): 
  - *Strongest positive correlation observed between energy per capita and [PPI_feature_name] in [Region]*.
  - *Weak or no correlation observed for [feature] across [regions]*.
  - *Regional patterns: [short summary of any region-specific trends]*

**How to run (quick)**
```bash
# 1) create & activate virtual env (optional)
python -m venv venv
source venv/bin/activate     # macOS/Linux
venv\Scripts\activate        # Windows

# 2) install dependencies
pip install -r requirements.txt

# 3) open notebooks
jupyter lab  # or jupyter notebook
