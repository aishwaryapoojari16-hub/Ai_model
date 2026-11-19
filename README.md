# AI Impact Mini-Project — Chapter 2

**Impact of AI: Both Positive and Negative** — data cleaning, preprocessing, EDA and model development on a 138-response survey.

Team: Avismyi · Aadhya · Aishwarya

## Repository layout
```
AI_Impact_Chapter2_Complete_Notebook.ipynb   # everything in one notebook (outputs included)
data/
  ai_impact_survey_raw.csv                   # original survey export (never edited)
  ai_impact_clean.csv                        # cleaned file produced by the notebook
graphs/                                      # all 21 figures (PNG)
tables/                                      # descriptive stats, correlations, MI ranking, model results (CSV)
docs/Chapter_2_AI_Impact_Revised_Work_Manual.pdf
requirements.txt
```

## What the notebook does
1. Dataset understanding (shape, columns, types)
2. Cleaning: short column names, missing/duplicate checks, spelling fixes (no rows removed)
3. EDA graphs (Figures 2.1–2.13)
4. Preprocessing: ordinal + one-hot encoding, Min-Max normalization, Z-score standardization, IQR outlier check
5. Statistics: descriptive table, correlation heatmap, mutual-information feature selection
6. Model development: baseline vs Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting, SVM; repeated stratified CV; grid-search tuning; hold-out evaluation; permutation importance

## Run it
```bash
pip install -r requirements.txt
jupyter notebook AI_Impact_Chapter2_Complete_Notebook.ipynb
```
Or open the notebook in Google Colab and upload `data/ai_impact_survey_raw.csv` when prompted.
