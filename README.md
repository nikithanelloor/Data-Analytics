# Zomato Restaurant Insights

**Data analysis & interactive dashboard using Python and Tableau**

## Tools Used
- **Python**: Pandas, Seaborn, Matplotlib for data cleaning & EDA  
- **Tableau**: Interactive dashboard building

##  Project Overview
This project analyzes Zomato restaurant data to uncover insights on:
- Restaurant geography, franchise presence, booking/delivery trends, vote counts, cuisine popularity, cost distribution, and ratings  
- Identification of “star” restaurants via key metrics

Built with Python for data cleaning and EDA, and Tableau for interactive dashboards.

---

##  Highlights
- Cleaned and validated data with **Pandas**, removing duplicates and handling missing values  
- Performed **EDA** using Pandas, Seaborn, Matplotlib to visualize geography, cost, ratings, and booking/delivery trends  
- Built a dynamic **Tableau dashboard** with filters, maps, charts, and KPIs to surface high-performing restaurants

##  Analytical Process

### 1. Data Cleaning & Preprocessing
- **Data loading** – Imported the Zomato dataset using Pandas.
- **Data cleaning** – Handled missing values, converted datatypes (e.g., ratings from string to float), and fixed inconsistencies.
- **Feature engineering** – Extracted attributes (e.g., cuisine count, booking flags) and standardized columns to shape the analytical dataset.

### 2. Exploratory Data Analysis (EDA)
- **Descriptive statistics** – Summarized distributions and data structure to understand trends.
- **Correlation analysis** – Examined relationships between key variables (e.g., cost vs. rating, booking vs. vote count) using correlation matrices. 
- **Data visualization** – Created bar charts, line graphs, histograms, and heatmaps (with Seaborn/Matplotlib) to highlight geographical trends, cuisine popularity, booking/delivery ratios, cost, and rating variations.

### 3. Dashboard Features
- **Dynamic filters** for rating threshold, votes, service options, and geography.
- **Highlight visuals** (maps, bar charts, KPI cards) that spotlight star restaurants.
- **Overview metrics** showing counts of starred venues by city/cuisine.
- **Criteria for “Star” Restaurants**
  Aggregate rating ≥ 4.5,
  Votes > 100,
  Offers both table booking and online delivery, and
  Widespread presence across cities or cuisines.


##  Insights
- **Mid-range pricing** captures most customer spend behavior.
- **Cost comparisons are imperfect**: Even after converting prices to INR, cross-country comparisons remain unfair due to regional differences in cost-of-living and price expectations. While average costs cluster under ₹6,000, outliers go as high as ₹800,000.
- **Price doesn’t drive ratings**: Low-cost restaurants don't necessarily have higher ratings. Instead, features like table booking and online delivery more strongly influence ratings.
- **Online delivery correlates with higher ratings**: Restaurants offering delivery tend to score higher on average.
- **Cuisine variety not crucial**: The number of cuisines offered doesn’t significantly impact ratings—restaurants with few cuisines can still achieve high ratings.
- **Ratings influenced by overall experience**: Correlation analysis reveals no single factor (max correlation <0.5) dominates ratings—service quality, consistency, and user experience drive ratings more.
- **Rating concentration**: Most restaurants have ratings between 3.5–4.0, indicating general satisfaction yet room for improvement.
- **Restaurant franchising**: Café Coffee Day, while mainly India-based, ranks as the first most globally listed brand in the data. Also Subway and Domino’s Pizza dominates worldwide, got second and third rank-validating their prominence in the Zomato dataset.

##  Conclusion & Recommendations

###  Conclusion  
The analysis revealed that:
- **Online delivery** and **table booking** correlate with higher ratings, reflecting evolving consumer expectations—even amid price and geography variations.  
- Most diners stick to a **mid-range budget (~₹150–300 per person)**—consistent with casual dining trends in India.  
- **No single factor** (cost, cuisine count, weather, etc.) strongly determines ratings; instead, holistic experiences like service, convenience, and reputation play the primary role.

###  Recommendations

1. **Enhance Online Presence**  
   Prioritize improving online ordering and delivery systems—70% of customers expect this as a standard, and those features often drive higher spend and satisfaction. 

2. **Focus on Mid-Range Pricing**  
   Promote options around ₹300 for two—84% of casual diners in India choose meals under ₹500, and this sweet spot aligns with both affordability and perceived value. 

3. **Target Dining Promotions**  
   Since dine-in venues receive more votes and ratings, restaurants should design special offers (e.g., loyalty programmes, themed events) to boost engagement and footfall.

4. **Build a Strong Reputation**  
   Invest in online reputation management; even a one-star rise in review can yield a 5–9% revenue increase, underscoring the value of quality and reviews. 



