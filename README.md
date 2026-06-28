# 🍿 Netflix Data Cleaning Project

## 📌 Overview

This project focuses on cleaning and preparing the Netflix Movies and TV Shows dataset using Python and Pandas.  
The dataset contains missing values, inconsistent formats, and unstructured data, which were cleaned to make it suitable for analysis.

---

## 🎯 Objective

- Explore and understand the dataset structure  
- Handle missing values properly  
- Fix incorrect data types  
- Extract useful information from messy columns  
- Prepare a clean dataset for further analysis  

---

## 📂 Dataset

The dataset contains information about Netflix movies and TV shows, including:

- Title  
- Type (Movie / TV Show)  
- Director and Cast  
- Country  
- Date Added  
- Release Year  
- Rating  
- Duration  
- Genre  
- Description  

Source: Kaggle Netflix Dataset

---

## 🧹 Data Cleaning Steps

- Loaded and inspected the dataset using Pandas  
- Checked missing values across all columns  
- Filled missing values using:
  - Mode for categorical columns  
  - "Unknown" for missing text data  
- Converted `date_added` column to datetime format  
- Extracted numeric values from `duration` column  
- Split duration into:
  - duration number  
  - duration unit (min / seasons)  
- Removed duplicate records  
- Standardized column names  
- Performed final validation to ensure dataset is clean  

---

## 📊 Final Dataset Status

- No duplicate records  
- No missing values  
- Clean and structured format  
- Ready for analysis  

---

## 🛠️ Tools Used

- Python  
- Pandas  
- Jupyter Notebook  

---

## 📁 Project Structure
