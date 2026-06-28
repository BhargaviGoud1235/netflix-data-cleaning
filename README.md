# 🍿 Netflix Data Cleaning & Exploratory Data Analysis Project

## 📌 Objective
This project focuses on cleaning, preprocessing, and analyzing the Netflix Movies and TV Shows dataset using Python.

The dataset contains real-world messy data with missing values, inconsistent formats, and mixed data types. The goal is to transform it into a clean dataset and perform exploratory data analysis (EDA).

---

## 🛠️ Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## 📊 Project Workflow

### 1️⃣ Data Loading
The Netflix dataset is loaded using Pandas and initial inspection is done using head(), info(), and shape.

---

### 2️⃣ Handling Missing Values
Missing values were handled as follows:
- director → filled with "Unknown"
- cast → filled with "Not Available"
- country → filled using mode
- rating → filled using mode

---

### 3️⃣ Date Conversion
The `date_added` column was converted into datetime format using pandas to enable time-based analysis.

---

### 4️⃣ Duration Cleaning
The duration column was split into two new features:
- duration_number → numeric value
- duration_unit → type (Minutes / Seasons)

---

### 5️⃣ Data Cleaning
- Removed duplicate records
- Standardized column names to lowercase
- Handled missing and inconsistent values

---

### 6️⃣ Feature Engineering
New features were created:
- year_added
- month_added

These help in analyzing content trends over time.

---

## 📈 Exploratory Data Analysis (EDA)

The following visualizations were created:

### 🎬 Movies vs TV Shows
Shows the distribution of Movies and TV Shows on Netflix.

### 🌍 Top 10 Countries
Shows countries producing the most Netflix content.

---

## 📊 Key Insights
- Netflix has more Movies than TV Shows
- United States produces the highest number of titles
- Netflix has a large amount of international content

---

## 💾 Output
The cleaned dataset is saved as:

data/netflix_cleaned.csv

---

## 🚀 How to Run This Project

Clone the repository:
git clone https://github.com/your-username/netflix-data-analysis.git

Install dependencies:
pip install -r requirements.txt

Run notebook:
jupyter notebook

---

## 📌 Conclusion
This project demonstrates real-world data cleaning, preprocessing, and exploratory data analysis using Python. It improves understanding of handling messy datasets and preparing them for analysis.

---

## ⭐ Future Improvements
- Add advanced visualizations
- Build dashboard using Power BI or Tableau
- Perform genre-based analysis
- Time series analysis of Netflix content

---

## 📜 License
This project is for educational purposes only.
