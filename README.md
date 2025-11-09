# <h1 align="center">🎥<br>[Netflix Movies Analysis - Data Analysis and Visualization](https://netflixmoviesanalysis.streamlit.app/)</h1>

## Overview 📋
![Front_Page](<Images/1.png>)
A comprehensive data analysis project exploring Netflix's content catalog using Python, focusing on various trends and patterns in movies and TV shows.<br>

This project analyzes Netflix's content library using data visualization and statistical analysis to uncover insights about movie durations, content distribution, and production trends. The analysis is presented through an interactive Streamlit dashboard (https://netflixmoviesanalysis.streamlit.app/)

## Features ✨
- Interactive filters (year range, genre)
- Distribution plots for movie durations
- Genre distribution bar chart
- Top countries producing content with percentage labels
- Boxplots of duration by genre
- Scatter plot showing relation between release year and cast size
- Word cloud of common words in titles
- Data table for exploration
## Installation 🛠️
### Quick start (run locally)

1. Create and activate a virtual environment (recommended):

Windows (PowerShell):

```powershell
python -m venv .venv; .\\.venv\\Scripts\\Activate.ps1
```

2. Install dependencies:

```powershell
python -m pip install -r requirements.txt
```

3. Start the Streamlit app:

```powershell
streamlit run app.py
```

4. Open the browser at: `http://localhost:8501`

## Requirements

This project uses Python 3.8+ and the following packages (see `requirements.txt`):

- streamlit
- pandas
- matplotlib
- numpy
- seaborn
- wordcloud



## Files of interest

- `app.py` — main Streamlit application
- `netflix.csv` — dataset used by the app (should sit in the repo root)
- `assets/` — contains `netflix_logo.png` and optional Lottie JSON

## Notes & troubleshooting

- If the app fails to start due to missing packages, run the install command above again.
- If images don't load, confirm the `assets/` directory exists and contains `netflix_logo.png`.
- The repository previously contained an unrelated README; this file now documents the Netflix Movies Analysis project.

## Contributing

Contributions welcome — open an issue or submit a PR.

## Contact

For questions: hemant0hack@gmail.com


