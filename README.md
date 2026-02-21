# 🛒 Amazon E-commerce Data Analysis & Cleaning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-green.svg)
![Matplotlib](https://img.shields.io/badge/Data-Visualization-orange.svg)

## 📌 Project Overview
This project focuses on transforming a messy, unstructured dataset of over 1,000 Amazon products and reviews into a clean, structured format. Beyond data wrangling, I performed Exploratory Data Analysis (EDA) and text analysis (NLP) to extract actionable business insights regarding pricing strategies, product popularity, and customer sentiment.

## 🎯 Business Questions Answered
* What are the top-selling and highest-rated product categories?
* How does the discount percentage impact the final user rating?
* Does a longer, detailed product description lead to higher customer trust and ratings?
* What are the most common pain points for customers giving negative reviews (≤ 3 stars)?

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Cleaning & Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Text Analysis:** `wordcloud`

## 🚀 Key Features & Workflow

### 1. Data Cleaning (Data Wrangling)
* **Data Type Casting:** Removed currency symbols (`₹`, `$`) and commas from pricing columns to convert them into functional `float` data types.
* **String Manipulation:** Parsed nested and complex product categories (e.g., `Electronics|Mobiles|Accessories`) to extract the **Main Category** for accurate grouping.
* **Missing & Anomalous Values:** Handled nulls and cleaned hidden characters in the ratings column.

### 2. Exploratory Data Analysis (EDA)
* Aggregated data to find the average rating and total product count per main category.
* Categorized discount percentages into tiers (Low, Medium, High) to analyze pricing strategies.
* Identified "Super Reviewers" by extracting and grouping active `user_id`s.

### 3. Sentiment & Text Analysis (NLP)
* Isolated reviews with low ratings (≤ 3 stars).
* Generated a **Word Cloud** to visualize the most frequent words in negative reviews, highlighting common customer complaints (e.g., packaging, delivery issues).

## 📊 Visualizations & Insights

*(Note: Add your screenshots here by dragging and dropping them into the GitHub editor)*

* **Top Product Categories:** ![Bar Chart Placeholder](link_to_your_image.png)
* **Price vs. Popularity:** ![Scatter Plot Placeholder](link_to_your_image.png)
* **Negative Reviews Word Cloud:** ![Word Cloud Placeholder](link_to_your_image.png)

## 💻 How to Run This Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/amazon-data-analysis.git](https://github.com/yourusername/amazon-data-analysis.git)
