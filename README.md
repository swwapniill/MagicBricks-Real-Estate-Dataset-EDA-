# 🏡 MagicBricks Real Estate — Exploratory Data Analysis (EDA)

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20|%20Seaborn%20|%20Matplotlib-orange)
![Report](https://img.shields.io/badge/Report-PDF-red)

A complete exploratory data analysis (EDA) on the **MagicBricks real-estate dataset**, focused on understanding price behavior, market patterns, and key drivers of property value.

This project is part of my data analytics portfolio — structured, clean, and visualization-driven.

---

## 📌 Project Overview
This analysis explores residential property data from MagicBricks, covering:

- Property price  
- Size (sqft)  
- BHK  
- Bathrooms & balconies  
- Furnishing details  
- Seller & transaction type  
- Listing date  
- Location & locality  

The goal was to uncover **patterns, correlations, trends, and price drivers** using statistical & visual techniques.

---

## 🛠 Tech Stack
- **Python**
- **Pandas / NumPy**
- **Seaborn & Matplotlib**
- **ReportLab (for PDF report)**

---

## 📊 Key Insights

### ⭐ **Univariate Insights**
- **Price** is right-skewed → most listings fall between **₹40L–₹1.6Cr**.
- **Size** distribution shows typical homes are **800–1500 sqft**.
- **2BHK & 3BHK** dominate the dataset (~70%).
- Majority units are **unfurnished or semi-furnished**.

---

### 🔗 **Bivariate Insights**
- **Price vs Size** → strong positive correlation.
- **Price vs BHK** → higher BHK means higher price, but overlapping ranges suggest **location impacts pricing** heavily.
- **Fully-furnished** units trend toward higher price brackets.
- **Brokers** dominate both resale & new listings (crosstab).

---

### 🔥 **Multivariate Insights**
- Price correlates strongly with → **Size**, **Bathrooms**, and **BHK**.
- Pairplots reveal distinct clusters for property types.
- Correlation matrix highlights amenities as strong predictors.

---

## 📈 Important Visualizations
- 📌 Histogram + KDE  
- 📌 Scatter plots  
- 📌 Boxplots & Violin plots  
- 📌 Countplots  
- 📌 Heatmaps  
- 📌 Correlation matrix  
- 📌 Pairplots  
- 📌 Line plot (Price over time)

---

## 📎 Project Files
| File | Description |
|------|-------------|
| `MagicBricks_EDA.ipynb` | Full EDA notebook |
| `MagicBricks.csv` | Input dataset |
| `README.md` | Project documentation |

---

## 🚀 Conclusion
The dataset reveals predictable real-estate patterns — larger homes, better furnishing, and additional amenities consistently command higher prices.  
Location introduces significant variation, making it a crucial hidden factor behind pricing.

---

## 🤝 Connect
If you want to collaborate, discuss analytics, or review the notebook — feel free to reach out!


