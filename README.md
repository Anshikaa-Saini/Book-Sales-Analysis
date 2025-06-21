# 📚 Book Sales - Exploratory Data Analysis (EDA)

This project explores a real-world dataset of book sales, aiming to uncover insights into publishing trends, author impact, ratings, and sales performance. The analysis leverages core Python libraries and visualization techniques to support decision-making for publishers, sellers, and readers.

---

## 📦 Dataset

- **Source**: [Kaggle - Book Sales and Ratings Dataset](https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings)  
- **Features Include**:
  - Book Name, Genre, Author, Publisher  
  - Average Rating, Rating Count  
  - Sale Price, Units Sold, Gross Sales  
  - Language Code, Publishing Year, Author Rating  

---

## 🎯 Project Objectives

- Perform data cleaning and preprocessing using Python.  
- Analyze trends in book sales, ratings, genres, and author influence.  
- Visualize correlations and distributions using intuitive plots.  
- Extract actionable insights relevant to publishers, marketers, and readers.  

---

## ⚙️ Workflow Summary

### 🔹 Data Cleaning
- Removed entries with missing book names  
- Filtered out records with publishing year ≤ 1900  
- Dropped duplicate records for cleaner analysis  

### 🔹 EDA Visualizations
- **Histograms**: Publishing year distribution  
- **Bar Plots**: Book counts by genre  
- **Box Plots**:  
  - Rating counts by genre  
  - Units sold by author rating  
- **Scatter Plots**:  
  - Sale price vs. units sold  
  - Average rating vs. rating count  
- **Pie Chart**: Language distribution  
- **Line Plot**: Units sold over publishing years  
- **Pair Plot**: Feature interaction overview  

### 🔹 Group-Based Insights
- Top authors based on total gross sales  
- Rating trends by author rating (average & variance)  
- Revenue performance analysis by publisher  

---

## 🛠 Tech Stack

- **Languages**: Python  
- **Libraries**: Pandas, Matplotlib, Seaborn  
- **Environment**: Jupyter Notebook  

---

## 📈 Key Insights

- 📌 **Genre and author rating** are strong indicators of a book’s sales performance  
- 📌 **Language diversity** is concentrated around a few dominant language codes  
- 📌 **Sales patterns** differ notably across authors and publishing years  
