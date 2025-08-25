# 📊 Netflix Dashboard Project

This project showcases an end-to-end data analysis and visualization of Netflix content using Python (Jupyter Notebook) and Power BI.

---

## 🚀 Project Overview

- 🔍 **Objective**: Analyze Netflix's content library to understand trends in content addition, ratings, countries, and content type.
- 📚 **Dataset**:  Netflix Movies and TV Shows Dataset (https://share.google/DjSof925dcPHBLvqv)
- 📅 Timeframe: Cleaned and analyzed up to 2023.

---

## Live Demo


Check out the interactive Netflix dashboard here:([https://your-live-demo-link.com](https://netflix-dashboard-project-879btxqjt7mytak2osckr8.streamlit.app/))

## 🛠 Tools Used

- 🐍 Python (Pandas, NumPy)
- 📓 Jupyter Notebook (Data Cleaning & Preprocessing)
- 📈 Power BI (Dashboard and Visualizations)
- 📁 Excel/CSV (Data Export for BI)

---

## 🧹 Data Cleaning Steps

- Removed rows with missing `title`, `date_added`, or `rating`
- Converted `date_added` to datetime format
- Extracted `year_added` from `date_added`
- Split `duration` into `duration_value` and `duration_unit`
- Trimmed whitespace and handled inconsistent entries

---

## 📊 Dashboard Highlights

- Total content added per year
- Distribution of Movies vs TV Shows
- Rating breakdown across content
- Top 10 content-producing countries
- Duration insights

> 🎯 Built using slicers, cards, bar charts, pie charts, and interactive visuals

---

## 📂 Project Files

File | Description 

| `netflix_cleaning.ipynb` | Data cleaning in Python |
| `netflix_cleaned_data.csv` | Cleaned dataset for visualization |
| `netflix_dashboard.pbix` | Power BI dashboard |

---

## 💡 Key Learnings

- Real-world data cleaning using Python
- Handling missing values and formatting issues
- Creating slicers, KPIs, filters, and dynamic visuals in Power BI
- Dashboard storytelling for better decision-making



