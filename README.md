# SpaceX Falcon 9 First-Stage Landing Prediction

A data science capstone project exploring whether the first stage of a SpaceX Falcon 9 launch successfully lands. The project follows a multi-step workflow: collecting launch data, preparing it for analysis, exploring patterns, visualizing results, and building classification models.

## Project objectives

- Collect historical Falcon 9 launch records from public sources.
- Clean and transform launch data for analysis.
- Explore relationships between launch characteristics and first-stage landing outcomes.
- Build and evaluate machine-learning classifiers for landing-success prediction.

## Repository notebooks

| Notebook | Purpose |
|---|---|
| `SpaceXDataCollectionWithWebScraping.ipynb` | Scrapes historical Falcon 9 launch records from Wikipedia using Requests, BeautifulSoup, and Pandas. |
| `SpaceX_DataCollection.ipynb` | Additional data-collection work for the capstone. |
| `SpaceXDataWrangling.ipynb` | Prepares and transforms launch data for analysis. |
| `SpaceXEDA.ipynb` | Exploratory analysis, including SQL-based investigation of the launch dataset. |
| `SpaceXEDAVisualization.ipynb` | Visual exploration of launch data and patterns. |
| `SpaceXInteractiveVisuals.ipynb` | Interactive visualizations of the data. |
| `SpaceXPredictive_Analysis.ipynb` | Builds classification models, including Logistic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors, to predict landing outcomes. |

## Tools and technologies

- Python
- Pandas and NumPy
- Requests and BeautifulSoup
- SQL / SQLite and SQLAlchemy
- Matplotlib and Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook / Google Colab

## Workflow

1. **Data collection:** Gather launch records from public sources and web scraping.
2. **Data wrangling:** Clean, structure, and prepare the data for analysis.
3. **Exploratory data analysis:** Use Python and SQL to investigate launch trends and relationships.
4. **Visualization:** Communicate patterns with static and interactive charts.
5. **Predictive modeling:** Train classification algorithms to estimate first-stage landing success.

## How to explore

Open the notebooks in the order above to follow the project from data collection through modeling. They can be viewed directly on GitHub or opened in [Google Colab](https://colab.research.google.com/).

## Project context

This repository contains work completed as part of an IBM Data Science capstone learning project. It is presented as a portfolio example of a complete applied data-science workflow.

## Future improvements

- Add a concise project summary with verified model metrics.
- Consolidate repeated data-preparation steps into reusable scripts.
- Add a data dictionary and document the final feature set.
- Include selected charts and explain the key findings in plain language.
- Add reproducible environment and setup instructions.
