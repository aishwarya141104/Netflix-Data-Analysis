
<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/df54b2ee-84ee-4efa-9037-6994dc43d58c" />

# 🎬 Netflix Data Analysis using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

Netflix has become one of the world's largest streaming platforms, offering thousands of movies and TV shows across different genres and countries. This project performs **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset to uncover meaningful insights about content distribution, ratings, genres, release trends, countries, and directors.

The analysis is performed using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**, demonstrating practical data cleaning, transformation, visualization, and business insight generation techniques.

---

# 🎯 Project Objectives

- Analyze the distribution of Movies and TV Shows
- Explore content production across different countries
- Identify the most common content ratings
- Discover the most popular genres
- Analyze Netflix content growth over time
- Find the directors with the highest number of titles
- Perform data cleaning and preprocessing
- Create informative visualizations for better decision-making

---

# 📂 Dataset Information

**Dataset Name**

Netflix Movies and TV Shows

**Source**

https://www.kaggle.com/datasets/shivamb/netflix-shows

**Dataset Size**

- Total Records: **8,807**
- Features: **12**

### Dataset Columns

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |

---

# 📁 Project Structure

```text
Netflix-Data-Analysis/
│
├── netflix_analysis.ipynb
├── README.md
├── LICENSE
├── requirements.txt
└── dataset/
    └── netflix_titles.csv
```

---

# 🔄 Project Workflow

```
Dataset Collection
        │
        ▼
Data Loading
        │
        ▼
Data Cleaning
        │
        ▼
Missing Value Handling
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Visualization
        │
        ▼
Business Insights
```

---

# 🧹 Data Preprocessing

The dataset was cleaned before analysis by performing the following tasks:

- Removed duplicate records
- Checked for missing values
- Converted date columns into datetime format
- Standardized column names
- Extracted year from date_added
- Split multiple country values where required
- Cleaned genre and director information

---

# 📊 Exploratory Data Analysis

The project answers several important business questions including:

### 1. Content Distribution

- Movies vs TV Shows
- Percentage of each content type

---

### 2. Country Analysis

- Top countries producing Netflix content
- Country-wise contribution

---

### 3. Rating Analysis

- Distribution of audience ratings
- Most common content certifications

---

### 4. Genre Analysis

- Most popular genres
- Frequency of genre categories

---

### 5. Content Growth

- Number of titles added every year
- Growth trend of Netflix library

---

### 6. Director Analysis

- Directors with the highest number of titles
- Contribution of top creators

---

# 📈 Visualizations Included

The notebook contains multiple visualizations including:

- Bar Charts
- Count Plots
- Horizontal Bar Charts
- Line Charts
- Distribution Plots
- Heatmaps (where applicable)

---

# 💡 Key Insights

### 📌 Content Type

- Movies significantly outnumber TV Shows on Netflix.

### 📌 Country

- The United States contributes the highest number of titles.
- India, the United Kingdom, Canada, and Japan are also major content producers.

### 📌 Ratings

- TV-MA and TV-14 are the most common content ratings.
- Netflix primarily targets mature audiences.

### 📌 Genres

- International Movies
- Dramas
- Comedies
- Documentaries

are among the most popular genres available.

### 📌 Content Growth

- Netflix experienced rapid content expansion after 2015.
- The highest number of titles were added between 2018 and 2020.

### 📌 Directors

Several directors have contributed multiple movies and TV shows, highlighting recurring collaborations with Netflix.

---

# 📚 Python Concepts Used

- Data Cleaning
- Data Transformation
- Missing Value Handling
- GroupBy Operations
- Sorting
- Filtering
- Value Counts
- Lambda Functions
- Datetime Operations
- Data Visualization
- Exploratory Data Analysis (EDA)

---

# ▶️ How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/aishwarya141104/Netflix-Data-Analysis.git
```

### Navigate to the Project Folder

```bash
cd Netflix-Data-Analysis
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
netflix_analysis.ipynb
```

and run all cells.

---

# 📦 Requirements

```
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
```

---

# 🚀 Future Improvements

- Build an interactive Power BI dashboard
- Develop a Tableau dashboard
- Perform sentiment analysis on descriptions
- Build a recommendation system
- Create a Streamlit web application
- Add predictive analytics using Machine Learning
- Deploy the project on the cloud

---

# 🎓 Learning Outcomes

This project demonstrates practical experience in:

- Exploratory Data Analysis
- Data Cleaning
- Python Programming
- Data Visualization
- Business Insight Generation
- Real-world Dataset Analysis
- Git & GitHub Project Management

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👩‍💻 Author

## **Aishwarya Kulkarni**

🎓 B.Tech Information Technology Student

📊 Data Analytics Enthusiast

### GitHub

https://github.com/aishwarya141104

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub. It helps others discover the project and motivates further development.

---
**Thank you for visiting this repository! Happy Learning! 🚀**
