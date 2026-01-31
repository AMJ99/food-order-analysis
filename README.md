# Food Orders Data Analysis

## Project Overview
This project analyzes a food orders dataset by combining order, user, and restaurant data. The final merged dataset enables exploration of:

- Order trends over time
- User behavior patterns
- City-wise and cuisine-wise performance
- Membership impact (Gold vs Regular)
- Revenue distribution and seasonality

## Files in the Repository

- `orders.csv` – Transactional order data
- `users.json` – User master data
- `restaurants.sql` – Restaurant master data
- `eda_food_delivery.ipynb` – Jupyter Notebook with analysis
- `final_food_delivery_dataset.csv` – Final merged dataset (optional)

## Steps Performed
1. Load CSV, JSON, and SQL datasets
2. Merge datasets using `user_id` and `restaurant_id` (Left Join)
3. Create final dataset containing order details, user info, and restaurant info
4. Perform exploratory data analysis (EDA) and derive insights

## How to Use
1. Clone the repository
```bash
git clone https://github.com/AMJ99/food-order-analysis.git
