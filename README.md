# 🎬 Exploring Film Industry Trends

This project analyzes a comprehensive movie dataset from Kaggle to uncover trends and patterns in the film industry. It focuses on understanding genre popularity, director success, and audience preferences, while also using machine learning to forecast box office performance and IMDb ratings. An interactive Tableau dashboard is developed to visualize insights effectively.

---

## 📌 Objectives

1. **Forecast Audience Demand** and guide content creation.  
2. **Optimize Budget Allocation** for enhanced return on investment (ROI).  
3. **Support Actor and Director Selection** for higher market appeal.  
4. **Assess Long-Term Market Viability** for franchise and sequel potential.  

---

## 📂 Dataset

- **Source:** [Kaggle - TMDb 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  
- **Files Used:**
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

---

## ⚙️ Technologies Used

- **Python:** Data preprocessing, feature engineering, machine learning models  
- **Pandas & NumPy:** Data manipulation  
- **Matplotlib & Seaborn:** Visualization  
- **Scikit-learn:** Model building and evaluation  
- **Tableau:** Interactive dashboard and final visualization  
- **Google Colab:** Collaborative coding and execution  

---

## 🔍 Methodology

1. **Data Cleaning:**
   - Removed duplicates and null values  
   - Extracted relevant fields like genres and director from nested data  

2. **Feature Engineering:**
   - Converted stringified lists into Python objects  
   - Extracted release year, created new columns like `success_rate`  

3. **Predictive Analysis:**
   - **Revenue Prediction** using Random Forest Regressor  
   - **Rating Prediction** using Linear Regression  

4. **Visualization:**
   - Generated insights and patterns using Tableau dashboards  

---

## 📊 Tableau Dashboard Highlights

| Figure | Visualization                                |
|--------|----------------------------------------------|
| Fig. 6.1 | Actual Revenue vs. Predicted Revenue by Genre |
| Fig. 6.2 | Budget vs. Revenue (Scatter Plot)            |
| Fig. 6.3 | Actual vs. Predicted Ratings                 |
| Fig. 6.4 | Total Movies by Countries (Map)              |
| Fig. 6.5 | Top 10 Genres (Bar Chart)                    |
| Fig. 6.6 | Popularity vs. Genres                        |
| Fig. 6.7 | Total Movies by Years                        |
| Fig. 6.8 | Final Combined Tableau Dashboard             |
| Fig. 6.9 | Director vs. Revenue                         |

---

## 🌐 Live Dashboard

[![Final Tableau Dashboard](https://github.com/ShafinMz08/Exploring-film-Industry-Trends/blob/main/images/dashboard.jpeg)](https://public.tableau.com/views/TMDb_movie_analysis/TMDb?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


---



```bash
![Dashboard Preview](images/final_dashboard.png)
