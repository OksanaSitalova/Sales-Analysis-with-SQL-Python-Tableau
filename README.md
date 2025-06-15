#  E-Commerce Sales Analytics with BigQuery, Python & Tableau

This project presents a full-cycle analysis of an online furniture store's performance using real session data from **Google BigQuery**. The analysis is performed in **Python** using Colab, and visualized via an interactive **Tableau Public** dashboard.

---

## Live Dashboard

👉 [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/oksana.sitalova/viz/Project_17484593647600/Dashboard1)

---

##  Project Goals

- Extract raw data using SQL from Google BigQuery
- Perform data cleaning, exploration, and advanced analytics in Python
- Visualize key metrics and patterns using Tableau
- Deliver insights about user behavior, geography, device types, and product sales

---

## Tools & Technologies

| Tool             | Purpose                              |
|------------------|--------------------------------------|
| Google BigQuery  | SQL-based data extraction            |
| Python           | Data analysis & preprocessing        |
| Pandas, NumPy    | Data manipulation                    |
| Matplotlib, Seaborn, Plotly | Data visualization       |
| Tableau Public   | Dashboard and storytelling           |
| Google Colab     | Cloud-based notebook environment     |

---

## Key Metrics & KPIs

- **Conversion Rate**: 9.59%
- **Total Revenue**: $953.30K
- **Average Order Value**: ~$954
- **Total Sessions**: 349,545
- **Purchases**: 33,538
- **Registered Users**: 27,945
- **Top Country**: United States
- **Top Category**: Sofas & Armchairs

---

## Analytical Highlights

### Geographic Insights

- **Americas** dominate sales (~$17.7M), followed by **Asia** and **Europe**
- **Top Countries**: USA, India, Canada, UK
- Smaller countries like Malta and Jamaica show **high conversion rates**

### Product Performance

- Most revenue from **Sofas & Armchairs**, **Chairs**, **Beds**
- Largest assortment: **Chairs** (211 unique products)

### Device & Traffic

- **Desktop** leads sales (59%), **Mobile** second (39%)
- **Organic Search** is the strongest channel
- **Guest users** make 91.9% of purchases

### Time-Based Patterns

- Peak sales in **December** (seasonal demand)
- Best days: **Tuesday & Wednesday**, worst: **weekends**

---

## Statistical Analysis

| Test                      | Purpose                                      | Result                  |
|---------------------------|----------------------------------------------|--------------------------|
| Pearson Correlation       | Sessions vs Revenue                          | r = 0.79 (strong)        |
| Shapiro-Wilk Test         | Normality of daily purchase distribution     | Not normal (p < 0.05)    |
| Mann–Whitney U Test       | Registered vs Guest daily purchase count     | Significant (p ≪ 0.001)  |
| Z-test for proportions    | Conversion rate difference (reg vs guest)    | Significant (0.4% diff)  |
| Channel & Category Correlations | Category/channel behavior patterns    | Moderate to strong       |

---

## Key Visualizations

- **KPI Tiles**: Sessions, Revenue, AOV, Conversion
- **Sales by Region**: Maps for World, Europe, Americas, Asia
- **Category Breakdown**: Top products and assortment size
- **User Segments**: Registered vs Guest, Subscribed vs Unsubscribed
- **Sales Dynamics**: Over time, by channel, device, and weekday
- **Correlation Heatmaps**: Traffic, geography, category interactions
