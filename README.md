
# Ramadan Desserts Survey Analysis 🍮

![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue)
![Python](https://img.shields.io/badge/Python-3.12-green)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-orange)

## 📊 Project Overview
This project analyzes customer preferences for Ramadan dessert brands using survey data. We explore brand popularity, pricing perceptions, and rating distributions through statistical analysis and visualizations.

## 📂 Dataset
The dataset contains 56 survey responses with these columns:
- `Previous Order`: Brands customers ordered from before
- `Pricing`: Customer perception (Fairly Priced/Over Priced)
- `Rating`: 1-5 scale ratings
- `Best Place`: Brands customers consider the best
- `Most Desired`: Brands customers most want to try

**Source**: [Ramadan_Desserts.csv](https://raw.githubusercontent.com/Patrickboules/ramadan-desserts-survey-analysis/main/Ramadan_Desserts.csv)

## 🔍 Key Findings

### 🏆 Brand Popularity
- **Top Ordered Brand**: BreadFast
- **Best Rated Brand**: BreadFast (27.8% of votes)
- **Most Desired Brand**: Fati's (12 votes)

## ⚗️ Hypothesis Testing Results

| Test | Null Hypothesis | p-value | Conclusion |
|------|-----------------|---------|------------|
| Pricing vs Rating | No relationship | 0.02 | Significant - Rating depends on pricing |
| Previous Order vs Best Order | No association | 0.01 | Significant association exists |

