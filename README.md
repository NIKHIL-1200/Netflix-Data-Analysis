# 📺 Netflix Data Analysis 

## 📌 Project Overview

This project analyzes the Netflix Movies and TV Shows dataset using Python to uncover valuable business insights. The analysis focuses on data cleaning, exploratory data analysis (EDA), and data visualization to understand Netflix's content library, production trends, audience targeting, and content growth.

The project demonstrates how Python can transform raw data into meaningful business insights using industry-standard data analysis libraries.

---

## 🎯 Objectives

- Clean and preprocess the Netflix dataset.
- Perform exploratory data analysis (EDA).
- Analyze Netflix's content distribution and trends.
- Create professional visualizations.
- Generate actionable business insights and recommendations.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Netflix Movies and TV Shows

Source:
https://www.kaggle.com/datasets/shivamb/netflix-shows

File Used:

- netflix_titles.csv

---

## 📁 Project Structure

```text
Netflix_Data_Analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── images/
│   ├── movies_vs_tvshows.png
│   ├── movies_vs_tvshows_pie.png
│   ├── top_10_countries.png
│   ├── top_10_genres.png
│   ├── top_10_directors.png
│   ├── content_released_by_year.png
│   ├── content_ratings_distribution.png
│   ├── movie_duration_distribution.png
│   ├── content_added_by_year.png
│   ├── content_added_by_month.png
│   └── movies_vs_tvshows_trend.png
│
├── Netflix_Data_Analysis.ipynb
├── Business_Insights.md
├── README.md
└── requirements.txt
```

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Renamed column names
- Converted `date_added` to datetime format
- Extracted:
  - Year Added
  - Month Added
- Split movie duration into:
  - Duration Value
  - Duration Unit
- Handled missing values where required
- Saved the cleaned dataset for analysis

---

## 📊 Business Questions Answered

1. What is the distribution of Movies vs TV Shows?
2. Which countries produce the most Netflix content?
3. Which genres are the most popular?
4. Which directors have the highest number of titles?
5. Which years had the highest number of content releases?
6. Which content ratings are most common?
7. What is the distribution of movie durations?
8. How has Netflix's content library grown over time?
9. Which month has the highest number of content additions?
10. How has Netflix added Movies and TV Shows over the years?

---

## 📈 Visualizations

The project includes multiple visualizations such as:

- Count Plot
- Pie Chart
- Bar Chart
- Horizontal Bar Chart
- Line Chart
- Histogram

Each visualization is saved inside the **images/** folder.

---

## 🔍 Key Business Insights

- Movies make up the majority of Netflix's content library.
- The United States contributes the highest number of titles.
- Drama and International genres are among the most common.
- A small number of directors contribute multiple titles.
- Netflix significantly expanded its content library in recent years.
- TV-MA is the most common content rating.
- Most movies have a standard feature-length duration.
- Content additions increased rapidly during Netflix's growth period.
- Content additions vary across different months, indicating seasonal release strategies.
- Movies remain the largest portion of the catalog, while TV Shows continue to grow steadily.

---

## 💼 Business Recommendations

- Continue investing in high-performing content categories.
- Expand regional and international content partnerships.
- Maintain a balanced mix of Movies and TV Shows.
- Increase investment in successful original series.
- Optimize content release schedules based on seasonal trends.
- Use viewer preferences and historical trends to guide future content acquisition.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Analysis
- Business Storytelling
- Python Programming
- Data-Driven Decision Making

---

## 🚀 How to Run the Project

1. Clone this repository.

```bash
git clone https://github.com/your-username/netflix-data-analysis.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells to reproduce the analysis.

---

## 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 🎯 Conclusion

This project demonstrates the complete data analysis workflow, from cleaning raw data to generating actionable business insights. Using Python and its data analysis libraries, the project uncovers trends in Netflix's content library, helping understand content distribution, audience targeting, and platform growth.

---

## 👤 Author

**Nikhil Uthaiah KR**

Aspiring Data Analyst

### Skills

- Python
- SQL
- Excel
- Power BI
- Pandas
- NumPy
- Matplotlib
- Seaborn
