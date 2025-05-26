Book Sales - Exploratory Data Analysis

This project is a basic Exploratory Data Analysis (EDA) of a book sales dataset aimed at uncovering insights into publishing trends, book ratings, sales performance, and author impact.

---Dataset
- Source: https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings
- Features include:
  - Book name, genre, author, publisher
  - Book average rating and rating count
  - Sale price, units sold, gross sales
  - Language code, publishing year, author rating

---Project Objectives
- Practice data cleaning and exploration using basic Python libraries.
- Analyze sales, ratings, and trends by genre, author, and year.
- Visualize correlations and distributions with appropriate plots.
- Develop insights that could be useful for publishers, sellers, and readers.
  
---Workflow Summary

--Data Cleaning
- Removed entries with missing Book Name
- Filtered out records with Publishing Year ≤ 1900
- Removed duplicate records

--EDA Visualizations
- Histograms: Distribution of publishing years
- Bar Plots: Number of books by genre
- Box Plots:
  - Book ratings count by genre
  - Units sold by author rating
- Scatter Plots:
  - Sale price vs. units sold
  - Average rating vs. rating count
- Pie Chart: Language distribution
- Line Plot: Units sold over publishing years
- Pair Plot: Visual summary of feature interactions

--Group-Based Insights
- Top authors by total gross sales
- Average and variance in ratings by author rating
- Publisher-wise revenue analysis

 ---Tech Stack
- Python libraries- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

---Key Takeaways
- Genre and author rating significantly influence sales performance.
- Language diversity is skewed towards a few dominant codes.
- Sales trends vary significantly across years and authors.
