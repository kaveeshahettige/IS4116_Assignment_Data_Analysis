# Marketing Campaign Analytics

## Project Overview

This project analyzes customer behavior and marketing campaign effectiveness using the Maven Marketing Campaign dataset. The goal is to identify customer characteristics, spending patterns, and engagement behaviors that influence campaign acceptance and purchasing decisions. Insights from this analysis can help businesses optimize marketing strategies, improve ROI, and target customers more effectively.

The analysis includes data preprocessing, exploratory data analysis (EDA), statistical analysis, customer segmentation, and predictive modeling.

---

## Dataset

- **Source:** Kaggle (Maven Marketing Campaign dataset)  
- **Size:** 2,240 customer records, 28 features  
- **Key Features:**  
  - Customer demographics: Age, Income, Education, Marital status, Country  
  - Purchasing behavior: Wines, Fruits, Meat, Fish, Sweets, Gold products  
  - Campaign responses: AcceptedCmp1–5, Response  
  - Customer complaints and engagement channels  

**File location:** `data/data.xlsx`

---

---

## Tools and Libraries

- **Python 3.x**  
- **Data Analysis & Manipulation:** `pandas`, `numpy`  
- **Data Visualization:** `matplotlib`, `seaborn`, `plotly`  
- **Machine Learning & Modeling:** `scikit-learn`  
- **Excel Handling:** `openpyxl`  


----------------------------------
## Analysis Workflow

## Data Loading & Preprocessing

- Loaded dataset from Excel and inspected for missing values, duplicates, and outliers.

- Converted Dt_Customer to datetime and encoded categorical variables for analysis.

## Exploratory Data Analysis (EDA)

- Analyzed distributions of Age, Income, and Spending.

- Investigated product category performance and customer purchasing channels.

- Examined campaign acceptance rates and relationships with demographics.

- Customer Segmentation

- Scaled Income and Total_Spending features using StandardScaler.

- Applied KMeans clustering to identify three distinct customer segments.

- Visualized clusters in static and interactive plots.

- Predictive Modeling

- Built a Logistic Regression model to predict campaign response.

- Identified top features influencing campaign acceptance.

##  Visualization & Interpretation

- Plots include histograms, scatterplots, bar charts, boxplots, heatmaps, and interactive plots.

- Findings interpreted for actionable business insights, such as targeting high-value customers or optimizing campaign strategies.

## Key Findings

- Majority of customers are middle-aged (average ~57 years) with mid-level income.

- Wines and meat products contribute the most to revenue.

- Customer spending patterns vary widely, indicating potential high-value and untapped opportunities.

- Historical campaign response is a strong predictor of future campaign acceptance.

- Higher income generally correlates with higher spending across multiple product categories.

- Store purchases are preferred over catalog or web channels.

- KMeans clustering revealed three distinct customer segments for targeted marketing.

- Logistic Regression highlighted key features influencing campaign acceptance.


## How to Use

1. **Clone the repository:**  
```bash
git clone https://github.com/kaveeshahettige/IS4116_Assignment_Data_Analysis.git
jupyter notebook notebooks/marketing_analysis.ipynb
```
Explore visualizations, run analyses, and interpret results.

This project is for educational and analytical purposes. Data source: Kaggle Maven Marketing Campaign Dataset.
