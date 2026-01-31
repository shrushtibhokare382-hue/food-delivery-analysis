# Food Delivery Data Analysis

## Overview
This repository contains the **final merged dataset** and a **Jupyter Notebook** analyzing food delivery orders. The analysis combines order details, user information, and restaurant data to generate insights such as revenue by city, cuisine performance, and user spending patterns.

---

## Files

1. **`final_food_delivery_dataset.csv`**  
   - The merged dataset combining:
     - `orders.csv` (order details)
     - `users.json` (user details)
     - `restaurants.sql` (restaurant details)
   - Contains columns like `order_id`, `user_id`, `restaurant_id`, `total_amount`, `membership`, `cuisine`, `rating`, etc.

2. **`food_delivery_analysis.ipynb`**  
   - Jupyter Notebook with:
     - Data loading
     - Data merging (using pandas)
     - Analysis for MCQs
     - Summary statistics and revenue insights

---

## Key Insights
- **Top city for revenue among Gold members:** Bangalore  
- **Cuisine with highest average order value:** Italian  
- **Quarter with highest total revenue:** Q4 (Oct–Dec)  
- **Total orders by Gold members:** 50  
- **Distinct users placing at least one order:** 10  

*(Full calculations and analysis are in the notebook.)*

---

## How to Use
1. Open the notebook in **Google Colab** or **Jupyter Notebook**.  
2. Upload the dataset file if prompted (or it will load directly from the repository).  
3. Run all cells to reproduce the analysis and outputs.

---

## Author
Srushti Bhokare
