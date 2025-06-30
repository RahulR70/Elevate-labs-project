#  IMDB Movies Analysis

This project explores a dataset of IMDB movies to uncover insights related to gross revenue, runtime, genres, and viewer sentiment. It demonstrates data cleaning, exploratory analysis, sentiment scoring, and predictive modeling using Python.

##  Dataset
- Source: `imbd.csv`
- Columns explored: Title, Genre, Runtime, Gross Revenue, IMDB Rating, Overview

##  Tools & Libraries
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** – for data analysis & visualization
- **NLTK**, **VADER Sentiment Analyzer** – for text sentiment analysis
- **Scikit-learn** – for linear regression modeling

##  Key Steps
1. **Data Cleaning**  
   - Removed commas in `Gross`, extracted numeric `Runtime`, dropped missing values.

2. **Exploratory Data Analysis**  
   - Visualized rating distributions, genre-wise gross trends, correlation heatmaps.

3. **Sentiment Analysis**  
   - Used VADER to analyze sentiment of movie overviews.

4. **Regression Modeling**  
   - Built a Linear Regression model to predict IMDB ratings from numeric features.

## Insights
- Higher runtime generally correlated with better ratings.
- Sentiment scores of overviews showed moderate influence on IMDB ratings.
- Top-grossing genres varied significantly with average runtime and sentiment polarity.

##  Files
- `imbd.csv` – dataset
- `imbd_movies_analysis.ipynb` – Jupyter notebook containing the entire workflow
- `report.pdf` – project summary with visuals and findings *(to be uploaded)*
