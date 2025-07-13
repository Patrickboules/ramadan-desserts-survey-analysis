Analysis of Ramadan Desserts Survey Project
This project analyzes survey data about Ramadan desserts from various bakeries and restaurants. Here's a comprehensive breakdown of the analysis:

Data Overview
The dataset contains 56 entries with 5 columns:

Previous Order: Brand previously ordered from (14 unique values)

Pricing: Pricing perception ("Fairly Priced" or "Over Priced")

Rating: Customer ratings (1-5 scale)

Best Place: Brand considered the best

Most Desired: Brand most desired for future orders


Key Visualizations
1. Brand Popularity
Previous Orders: BreadFast was most frequently ordered (bar chart)

Best Place: BreadFast also most frequently mentioned as best (pie chart - 27.8%)

Most Desired: Visualized via treemap showing Fati's (12 votes), BreadFast (9), and Sultana (6) as top choices

2. Ratings Analysis
Rating distribution showed most reviews were 5-star (25 reviews), followed by 4-star (15 reviews)

Boxplot showed "Fairly Priced" establishments had higher median ratings than "Over Priced" ones

3. Pricing Perception
68.5% (37) respondents considered restaurants "Fairly Priced"

31.5% (17) considered them "Over Priced"

Stacked bar chart showed pricing perception by previous order brand

Hypothesis Testing
Test 1: Pricing vs Rating
Null (H₀): Rating independent of Pricing

Alternate (H₁): Rating affected by Pricing

Result: Kruskal-Wallis test showed significant association (p < 0.05) - rejected H₀

Conclusion: Pricing strategy affects customer ratings

Test 2: Previous Orders vs Best Place
Null (H₀): No association between previous orders and best place

Alternate (H₁): Association exists

Result: Chi-square test showed significant association (p < 0.05) - rejected H₀

Visualization: Heatmap showed customer switching behavior between brands

Conclusion: Past purchasing behavior influences perception of "best" bakery

Key Findings
BreadFast dominates in both previous orders and "best place" mentions

Fair pricing correlates with higher ratings

Fati's is the most desired brand despite not being the most ordered

Strong association exists between where customers previously ordered and where they consider the best

Technical Notes
Used Python libraries: pandas, numpy, matplotlib, seaborn, squarify, scipy

Visualizations include bar charts, pie/donut charts, treemaps, boxplots, and heatmaps

Applied statistical tests: Kruskal-Wallis and Chi-square tests

This analysis provides valuable insights for bakery owners about customer preferences, pricing strategies, and brand perception in the Ramadan desserts market.
