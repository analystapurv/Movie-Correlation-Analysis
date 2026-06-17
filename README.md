# Movie-Correlation-Analysis
Exploratory Data Analysis (EDA) and Correlation Matrix using Python to analyze the movie industry dataset.
🎬 Movie Industry Gross Revenue Analytics: Exploratory Data Analysis (EDA)

Author: Apurv Chaudhari

Role: Data Analyst

Tech Stack: Python (Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebooks

📌 Executive Summary

In the high-stakes movie industry, production studios must strategically allocate millions of dollars in capital. The objective of this project is to analyze historical movie data (1986–2016) to determine which specific variables—such as production budget, company, or user engagement—have the highest mathematical correlation to a movie's final gross revenue.

By identifying these key drivers, studios can make data-informed decisions on where to invest their capital to maximize box office returns.

🛠️ Data Engineering & Cleaning

Data Ingestion: Imported a dataset of 7,000+ movies using Pandas.

Data Cleansing: Identified and dropped missing/null values, standardized data types (e.g., converting budget floats to integers for cleaner analysis), and removed duplicate records to ensure data integrity.

Feature Engineering: Cleaned and formatted release date strings to extract accurate release years for time-series analysis.

📊 Key Business Insights & Statistical Findings

Using Python's Seaborn and Matplotlib libraries, I generated scatter plots and a comprehensive Pearson Correlation Matrix.

Top Findings:

Budget vs. Gross Revenue (High Correlation): Found a strong positive correlation (0.74) between the production budget and final gross earnings. This statistically proves that higher upfront capital investment is the most reliable predictor of box office success.

User Engagement vs. Gross Revenue (High Correlation): Discovered that IMDB User Votes also share a high correlation (0.61) with gross revenue. Business Takeaway: Marketing spend focused on driving early audience engagement/voting is nearly as critical as the production budget itself.

Company vs. Gross (Low Correlation): Surprisingly, the specific production company had almost zero correlation to the movie's financial success, indicating that brand name alone does not guarantee box office performance.

🚀 Visualizations Included in the Notebook

Scatter Plots: Visualizing the direct linear relationship between Budget and Gross Revenue.

Heatmaps: A fully rendered Pearson Correlation Matrix visualizing the mathematical relationships across all numerical features.
