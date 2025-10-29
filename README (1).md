# 🎬 Movie Data Analysis

This project performs an **Exploratory Data Analysis (EDA)** on a movie dataset to uncover insights about movie genres, ratings, and audience preferences. The analysis is done using **Python**, leveraging libraries such as Pandas, Matplotlib, and Seaborn for data wrangling and visualization.

---

## 🧠 Project Overview
The dataset contains over **9000 movies** with attributes like:
- **Title**
- **Genre**
- **Popularity**
- **Vote Count**
- **Vote Average**
- **Release Date**
- **Original Language**
- **Overview**
- **Poster URL**

The goal is to clean, process, and analyze this data to find patterns and trends in the film industry.

---

## 🧹 Data Cleaning & Preparation
Key preprocessing steps include:
- Handling missing values in **Title**, **Genre**, and **Language**
- Converting **Release Date** into year format for trend analysis  
- Removing unnecessary columns (`Overview`, `Original_Language`, `Poster_URL`)
- Converting **Genre** entries from comma-separated lists into individual categories  
- Handling outliers and inconsistent numerical values in `Popularity`, `Vote_Count`, and `Vote_Average`

---

## 📊 Exploratory Data Analysis
The analysis focuses on:
- **Genre distribution** across the dataset  
- **Average ratings per genre**  
- **Popularity trends over release years**  
- **Vote count vs. rating correlation**  

Visualizations include:
- Bar charts for genre frequency  
- Scatter plots for rating vs popularity  
- Correlation heatmaps for numerical variables  

---

## ⚙️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Danny20111/movie-data-analysis.git
   ```
2. Navigate to the folder:
   ```bash
   cd movie-data-analysis
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook movie_data_analysis.ipynb
   ```

---

## 💡 Insights
- Certain genres dominate both in frequency and popularity  
- Movies with higher **vote counts** generally have more consistent ratings  
- Release year trends show a rise in movie production and audience engagement  
- Outliers in popularity indicate blockbuster releases  

---

## 🧩 Future Enhancements
- Incorporate IMDb or TMDb API for richer metadata  
- Build machine learning models to predict movie ratings  
- Add interactive dashboards using **Plotly** or **Tableau**

---

## 👤 Author
**Deepanshu Sahijwani**  
📍 Ahmedabad, India  
📧 [Deepanshusahijwani@gmail.com](mailto:Deepanshusahijwani@gmail.com)  
🔗 [GitHub: Danny20111](https://github.com/Danny20111)
