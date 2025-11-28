📑 Table of Contents

About the Project

Dataset

Data Cleaning & Preprocessing

Analysis & Visualizations

Key Insights

Repository Structure

How to Run the Project

Future Improvements

Contact

⭐ About the Project

This repository contains an end-to-end EDA project on Google Play Store data. The objective is to understand the behavior of mobile applications, identify top-performing categories, analyze user engagement, and uncover what contributes to an app's success.

This project is ideal for:

Data Science portfolios

Beginners learning EDA concepts

Recruiters evaluating analytical thinking

App developers studying market trends

📂 Dataset

The dataset includes the following features:

App, Category, Rating, Reviews

Size, Installs, Type, Price

Content Rating, Genres

Last Updated, Current Version, Android Version

The raw dataset was messy, requiring thorough cleaning to make it usable.

🧹 Data Cleaning & Preprocessing
Key Steps Performed

Removed duplicates and missing values

Cleaned numeric columns using regex and mapping

Converted Installs, Reviews, Price, Size into proper numeric formats

Standardized categories and genres

Converted data types for accurate analysis

📊 Analysis & Visualizations

The notebook includes:

Category distribution and dominance

Rating distribution and outlier detection

Install pattern analysis

Paid vs Free pricing comparison

Correlation matrix for numeric relationships

Trend analysis by last update date

Genre-based performance insights

All visualizations are built using Matplotlib, Seaborn, and Plotly Express for interactivity.

🎯 Key Insights

Free apps dominate the install ecosystem.

Game-related genres have the highest presence and user activity.

Smaller app sizes attract more downloads.

Apps updated recently perform better in review counts.

Paid apps receive higher ratings, likely due to niche user expectations.

📁 Repository Structure

├── data/
│   └── Google_PlayStore.csv
├── notebooks/
│   └── Google_PlayStore_Analysis.ipynb
├── images/
│   └── charts & visualizations
├── README.md
└── Executive_Summary.md

🚀 How to Run This Project

Install dependencies
pip install -r requirements.txt
Open the notebook
jupyter notebook Google_PlayStore_Analysis.ipynb

🔮 Future Improvements

Build a machine learning model to predict app rating or install count.

Add interactive dashboards using Streamlit or Power BI.

Perform sentiment analysis on user reviews.

Compare Google Play Store trends with Apple App Store data.

📧 Contact

Author: Meenakshi Rajpurohit

Email: imeenakshii28@gmail.com

GitHub: https://github.com/meenakshi-12345

Feel free to reach out for collaborations, suggestions, or discussions!
