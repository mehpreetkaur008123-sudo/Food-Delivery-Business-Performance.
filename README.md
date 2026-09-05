# Food Delivery Business Performance — Visualization Portfolio

A complete data visualization portfolio built with Matplotlib and Seaborn, exploring a food delivery business performance dataset to uncover trends, patterns, and relationships across orders, revenue, marketing spend, delivery time, and customer ratings.

## Files in This Repository

| File | Description |
|---|---|
| `Food_Delivery_Business_Performance.csv` | Raw dataset — 360 order batches across 8 cities, 6 cuisines, 3 order channels, and 4 weather conditions |
| `food_delivery_visualization_portfolio.ipynb` | The Jupyter notebook containing the full visualization portfolio and interpretations |

## What's Covered

- **Line plot** — monthly orders and revenue trend
- **Bar charts** — average revenue by city and by cuisine
- **Scatter plots** — marketing spend vs. revenue, delivery time vs. customer rating
- **Histograms** — distribution of customer rating, delivery time, and revenue
- **Box plots** — delivery time by weather, revenue by order channel
- **Violin plot** — customer rating distribution by cuisine
- **Count plots** — order batch frequency by channel and by weather
- **Correlation heatmap** — relationships across all key numeric metrics
- A brief interpretation follows every visualization
- **5 key business insights** and **7 practical recommendations** for management, both grounded in the actual computed results

## How to Run

Open `food_delivery_visualization_portfolio.ipynb` Jupyter Notebook. Make sure `Food_Delivery_Business_Performance.csv` is uploaded to the same environment/folder before running, since the notebook reads it by filename.

## Key Findings

- Delivery speed is the strongest driver of customer rating (r ≈ -0.88), and rating strongly predicts repeat customer percentage (r ≈ 0.82) — a clear speed-to-loyalty chain.
- Marketing spend only weakly correlates with revenue (r ≈ 0.20); order volume and average order value matter far more.
- Rainy weather increases average delivery time (38.75 vs. 29.99 minutes) and lowers average rating (4.23 vs. 4.53) compared to clear weather.
- Revenue varies substantially by city (~₹49,500–72,700) and cuisine (~₹46,800–73,400).
- The App channel leads in both order volume (59% of batches) and revenue.
