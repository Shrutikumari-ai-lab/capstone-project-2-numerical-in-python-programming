<p align="center">
  <img src="almabetter-logo.png" alt="AlmaBetter Logo" width="220">
</p>

🎬 Amazon Prime TV Shows and Movies — Exploratory Data Analysis
📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Amazon Prime Video content library, covering more than 9,000 movies and TV shows available in the United States. The goal is to uncover meaningful insights into content trends, audience preferences, and platform diversity to support data-driven business decisions.

Project Type: EDA Contribution: Individual

🎯 Problem Statement

The rapid growth of streaming platforms has resulted in vast content libraries, making it difficult to understand content trends, audience preferences, and performance without structured analysis. Amazon Prime Video hosts thousands of titles across genres, countries, and release years, with detailed ratings, popularity, and cast information — all of which can reveal valuable patterns for business decision-making.

💼 Business Objective

To analyze Amazon Prime Video's content library and generate actionable insights that support:

Understanding content distribution (movies vs. TV shows)
Identifying top-performing genres, countries, and titles
Evaluating audience satisfaction through IMDb/TMDB ratings
Informing future content acquisition and investment strategy
🗂️ Dataset

Two datasets are used:

Dataset	Description
titles.csv	Title-level details — id, title, type, release year, runtime, genres, production countries, IMDb/TMDB ratings, popularity, age certification
credits.csv	Cast & crew details — person id, title id, name, role (actor/director), character
🛠️ Tech Stack
Python
Pandas & NumPy — data manipulation
Matplotlib & Seaborn — visualization
Jupyter Notebook
🔍 Project Workflow
Know Your Data — shape, info, duplicates, missing values
Understanding Your Variables — column descriptions, unique values
Data Wrangling — duplicate removal, missing value imputation, type conversion
KPI Calculation — 10 business KPIs covering content health, audience satisfaction, diversity, growth, and premium content
Data Visualization — 16 charts across univariate, bivariate, and multivariate analysis
Business Recommendations & Conclusion
📊 Key Insights
Movies make up ~86% of the content library, with TV Shows a much smaller share.
Content production grew rapidly after 2010, peaking between 2018–2021.
Most titles fall in the 5–7 IMDb/TMDB rating range; very few titles score above 8.
The US and India are the top two content-producing countries.
Drama, Comedy, and Thriller are the most common genres.
TV Shows tend to have slightly higher median ratings than Movies, despite Movies dominating in volume.
Runtime shows little to no correlation with IMDb ratings.
💡 Recommendations
Increase investment in original TV Show content to boost engagement and retention.
Continue prioritizing popular genres (Drama, Comedy, Thriller) while expanding underrepresented ones.
Diversify content sourcing beyond the top production countries to grow global appeal.
Use quality (ratings) rather than runtime as a primary content investment signal.
📁 Repository Structure
├── Amazon_Prime_TV_Shows_and_Movies.ipynb   # Full EDA notebook
├── titles.csv                               # Titles dataset (not included — add your own)
├── credits.csv                              # Credits dataset (not included — add your own)
└── README.md
🚀 How to Run
Clone this repository
Install dependencies:
bash
   pip install pandas numpy matplotlib seaborn
Place titles.csv and credits.csv in the project root
Open and run Amazon_Prime_TV_Shows_and_Movies.ipynb in Jupyter Notebook / JupyterLab / Google Colab
✅ Conclusion

The analysis shows that while Movies dominate Amazon Prime Video's catalog in volume, TV Shows generally achieve slightly higher audience ratings. Content production has grown significantly over the last decade, reflecting continuous platform investment. These insights can guide smarter content acquisition, genre diversification, and regional expansion strategies going forward.
