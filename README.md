# 📊 Laptop E-commerce Market Analysis

**End-to-End Data Analysis Pipeline** analyzing 774 laptop listings to uncover pricing trends, hardware preferences, brand performance, discount strategies, and customer ratings.

## 🏢 Business Problem

**Objective**: Understand laptop market dynamics to inform pricing, inventory, and promotional strategies for an e-commerce platform.

**Key Questions**:
- Which brands/models dominate the market?
- What are the most popular hardware configurations (RAM/Storage)?
- How do discounts impact pricing and ratings?
- Which price segments deliver best value-for-money?

## 📁 Dataset Overview

**Source**: 774 laptop listings from e-commerce platform.
**Columns**: 9 features including Brand, Device Name, OS, RAM (GB), Storage (GB), Price (₹), Discount (%), Rating, Warranty

## 🛠️ Technical Pipeline

Raw Data → Extraction → Cleaning → EDA → Visualization → Hypothesis Testing


## 🔍 Key Findings

 1. **Market Leaders**
 2. **Hardware Preferences**
 3. **Pricing & Discounts**
 4. **Customer Satisfaction**

|    Metric   |   Value   |
|-------------|-----------|
| Price Range | ₹12,490 - ₹1,14,100 |
| Avg Price   | ₹51,699 |
| Avg Discount | 28.6% |
| Avg Rating | 4.12/5 |
| Top Brands | Samsung (171), HP (127), Lenovo (109) |
| Top Config | 512GB SSD (89%), 8-16GB RAM (91%) |


## 📈 Visualizations

Visuals are Generated via notebook(Visualisations.ipynb) using python libraries such as matplotlib, seaborn, Scipy.

## 🎯 Business Insights

1. **Stock 512GB SSD + 8-16GB RAM configs** - represent 90%+ market demand
2. **Focus promotions on ₹40K-70K segment** - optimal value/ratings balance
3. **Samsung/HP inventory priority** - market leaders with proven demand
4. **Leverage 30-50% discounts** - proven to drive sales volume

## 👨‍💻 Tools and Technologies Used

```python
pandas, numpy, matplotlib, seaborn, scipy.stats
Jupyter Notebook, Python 3.8+
