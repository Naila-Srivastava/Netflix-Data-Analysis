# 📺 Netflix Data Analysis Project

Welcome to my Netflix Data Analysis project! This project dives into the Netflix catalogue to uncover content trends, top genres, and viewer-friendly insights using Python, pandas and visualization tools like seaborn and matplotlib.

## 🧠 Objective
To explore and analyze Netflix's dataset through:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Visualizations for key trends
- Feature engineering
- Potential steps for future machine learning applications

## 🔧 Tools & Technologies
- Python (Pandas, NumPy, scikit-learn)
- Matplotlib & Seaborn
- Tableau Public (for interactive dashboards)
- Jupyter Notebook
- GitHub (for version-control)

## 📁 Dataset
This project uses Netflix data for EDA and ML.  
Due to size/privacy, the dataset isn't included in this repo.    

➡️ [Download dataset here] (https://www.kaggle.com/datasets/nailasrivastava/netflix-data-analysis-datasets)

## 💻 How to Run
1. Clone the repo  
2. Install dependencies: 'pip install -r requirements.txt'  
3. Open the notebook: 'netflix_analysis.ipynb' 
4. Run all cells and enjoy the visuals + ML magic!

## 📊 Key Analysis
- Content type distribution (Movies vs. TV Shows)
- Release year trends
- Country-wise content distribution
- Genre frequency
- Content ratings analysis
- Top featured directors

## 📈 Sample Visualizations
- Bar chart: Content type distribution
- Line plot: Content trends over time
- Pie chart: Rating breakdown
- World map (via Tableau): Country-wise content view

## 🌍 Advanced Visuals
- Interactive Tableau dashboards
- Country-based high-rated content map
- Rating-wise pie chart

## 📍 Feature Engineering
- Extracted duration in minutes
- Count of genres per title
- Machine Learning-based recommender system using TF-IDF and Cosine Similarity
- Interactive input: User enters a title and receives recommendations

## ✨ Recommendation System
Try typing a movie/TV show title at the bottom of the notebook to get personalized recommendations!

This interactive recommender brings a personalized touch to the project, blending natural language processing and user input to simulate a mini Netflix engine.

## 📝 Key Takeaways
- Netflix has a significantly higher number of movies than TV shows.
- Most content was added in recent years (post-2010).
- The United States dominates in content production, but international content is increasing.
- TV-14 and TV-MA are among the most common content ratings.
- A few directors frequently appear across the catalog.

## 📁 Project Structure
```plaintext
netflix-analysis/
│
├── netflix1.csv                           # Raw dataset
├── .gitignore                             # Required packages and libraries
├── netflix_cleaned_dataset.csv            # Cleaned dataset
├── visuals/                               # All charts and graphs
├── README.md                              # This file
├── requirements.txt                       # Required packages and libraries
└── Netflix_analysis.ipynb                 # Main analysis notebook
