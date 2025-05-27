# IPhone-Data-analysis

# 📱 iPhone Sales Analysis Project

This project performs a detailed analysis of iPhone sales data to extract insights into pricing trends, discount behavior, ratings, and customer feedback. The project follows a structured approach aligned with a standard data visualization rubric for academic or industry evaluation.

## 🔍 Objective

- Analyze iPhone product data including Sale Price, MRP, Ratings, Reviews, and Discounts.
- Identify key trends, outliers, and product performance.
- Create meaningful visualizations to communicate findings.

---

## 📁 Dataset

The analysis is based on the `apple_products.csv` dataset, which includes:
- **Product Name**
- **Sale Price**
- **MRP (Maximum Retail Price)**
- **Discount Percentage**
- **Rating**
- **Number of Ratings**
- **Number of Reviews**

---

## 📊 Analysis Breakdown

### ✅ 1. Cleaning and Handling Missing Values
- Identify and visualize null values
- Drop or impute missing entries

### ✅ 2. Feature Selection and Engineering
- Derive features such as `DiscountAmount` and `DiscountPercent`

### ✅ 3. Ensuring Data Integrity and Consistency
- Normalize product names
- Validate numerical data formats

### ✅ 4. Summary Statistics and Insights
- Descriptive statistics across major features
- Product and price-based aggregation

### ✅ 5. Identifying Patterns, Trends, and Anomalies
- Price vs Rating plots
- Trend analysis on most/least popular models

### ✅ 6. Handling Outliers and Data Transformations
- Use of boxplots and histograms to detect price/review outliers

### ✅ 7. Visual Representation of Key Findings
- Heatmaps, scatter plots, bar charts
- Correlation analysis

---

## 📂 Files Included

- `iPhone_Sales_Analysis_Rubric_Based.ipynb` – Main analysis notebook
- `apple_products.csv` – Dataset used for analysis
- `README.md` – Project overview and documentation

---

## 📌 Dependencies

Ensure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn
