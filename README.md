# Financial News and Stock Price Analysis
This repository hosts code for analyzing the Financial News and Stock Price Integration Dataset (FNSPID) to explore correlations between news sentiment and stock price movements. Developed as part of the B5W1 challenge by Nova Financial Solutions, the project includes Exploratory Data Analysis (EDA), technical indicator calculations using TA-Lib, sentiment analysis with TextBlob, and correlation studies to enhance predictive analytics.
Purpose
The goal is to quantify news sentiment, compute technical indicators (e.g., MA, RSI, MACD), and assess their impact on stock returns, supporting actionable investment strategies for financial forecasting.

## Repository Structure

.vscode/: VS Code settings (e.g., settings.json).
.github/workflows/: CI/CD configuration (e.g., unittests.yml).
.gitignore: Files to exclude from version control.
requirements.txt: Python dependencies.
README.md: Project overview and instructions.
src/: Source code (e.g., __init__.py).
notebooks/: Jupyter notebooks (e.g., eda_and_sentiment_analysis.ipynb, quantitative_analysis_with_technical_indicators.ipynb).
tests/: Unit tests (e.g., __init__.py).
scripts/: Additional scripts (e.g., __init__.py).
data/: Data files (e.g., raw_analyst_ratings.csv, stock CSVs).

How to Run and Utilize the Code

## Setup Environment:

Clone the repository: git clone https://github.com/oliyad-mulugeta/financial-news-analysis.git.
Navigate to the directory: cd financial-news-analysis.
Install dependencies: pip install -r requirements.txt (requires Python 3.8+).
Install TA-Lib (see TA-Lib installation if needed).


## Prepare Data:

Place FNSPID data (raw_analyst_ratings.csv) and stock price CSVs (e.g., AAPL.csv) in the data/ directory.
Update file paths in notebooks if your structure differs (e.g., ../data/news_with_sentiment.csv).


Run Notebooks:

Open notebooks/eda_and_sentiment_analysis.ipynb for EDA and sentiment scoring.
Open notebooks/quantitative_analysis_with_technical_indicators.ipynb for technical indicators and correlation analysis.
Execute cells sequentially, ensuring data files are accessible.


Utilize Results:

Review plots and tables (e.g., correlation results) in the notebooks.
Export data (e.g., merged_data.to_csv('data/results.csv')) for further analysis or strategy implementation.
Use insights for trading decisions (e.g., combining sentiment with RSI).



## Contribution Guidelines

Branching: Create feature branches (e.g., feature/eda-enhancement) from main. Use task-1, task-2, task-3 for challenge tasks.
Commit Messages: Follow Conventional Commits (e.g., feat: add sentiment scoring, fix: resolve timezone issue, docs: update README). Commit at least three times daily with clear, descriptive messages.
Pull Requests (PRs): Submit PRs from feature branches to main with a summary. Request reviews via GitHub Issues.
Code Standards: Adhere to PEP 8, include docstrings, and add unit tests in tests/ (e.g., using unittest).
Issues: Report bugs or suggest enhancements via GitHub Issues, tagging team members.

## Dependencies

Python 3.8+
pandas, numpy, textblob, talib, pynance, matplotlib, seaborn, scikit-learn, scipy
Listed in requirements.txt

## References

TA-Lib: https://github.com/mrjbq7/ta-lib
PyNance: https://github.com/mqandil/pynance
TextBlob: https://textblob.readthedocs.io/en/dev/
Git Conventions: https://www.conventionalcommits.org/