# Fantasy Premier League 2024/2025 Data Analysis
This project presents an exploratory data analysis (EDA) of the **Fantasy Premier League** (FPL) 2024/25 season.   
It aims to uncover trends, player performance patterns, and value insights to support better decision-making for FPL managers.

## Project objectives
1. **EDA on player performance**: `points`, `value`, `selection` trends
2. **Value-for-money analysis** (because budget is pain)
3. **Tracking consistency** vs **explosive picks**
4. Gameweek-by-gameweek evolution
5. **Custom visualizations** to spot under-the-radar gems
6. Prepare a foundation for **future predictive** or optimization models

## Contents
- `notebooks/fantasy_premier_league_24_25_analytic.ipynb`: main Notebook containing the full analysis
- `data/`: cleaned or transformed datasets used in analysis
- `data/data_description.md`: documentation of dataset fields and structure
- `outputs/insight_summary.md`: key insights and findings from the analysis
- `outputs/images/`: exported visualizations used to support conclusions
- `requirements.txt`: list of Python packages required to run the notebook
- `README.md`: project overview and usage guide

## Tools used
- **Python**: `IPython`, `re`, `nbformatos`, `request`, `os`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `numpy`, `plotly`, `pypalettes`, `pulp`, `mplsoccer`, `itertools`
- **Jupyter Notebook**
- **Data collected** from user `https://github.com/vaastav/` (*this is the man* 👏)

## Future work
- Add team **selection optimizer** based on players' `value` and `points`
- Include transfer analysis and `chip` usage impact
- Build a **model automatically** playing FPL `gameweek` by `gameweek`

## Notes
- This dataset covers player data across all 38 gameweeks of the 2024/25 FPL season.
- The analysis is intended for learning purposes, performance tracking, and supporting practical FPL planning throughout the full season.

---
> “Data won't pick your captain, but it might stop you from benching 20 points again.” – probably me

🫵🫵 Feel free to explore, fork, or suggest improvements.
