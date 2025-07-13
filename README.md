# Ramadan Desserts Survey Analysis

## Overview
Analysis of 56 customer surveys about Ramadan dessert preferences, pricing perceptions, and brand loyalty across various bakeries.

## Data Description
**Columns:**
- Previous Order (14 unique brands)
- Pricing ("Fairly Priced" or "Over Priced")
- Rating (1-5 scale)
- Best Place (brand considered best)
- Most Desired (brand desired for future orders)

## Key Findings

### Brand Performance
**Top 3 Previously Ordered:**
1. BreadFast - 12 orders
2. Crème - 6 orders  
3. Sale Sucre - 5 orders

**Most Desired Brands:**
1. Fati's - 12 votes
2. BreadFast - 9 votes
3. Sultana - 6 votes

### Pricing Perception
| Category       | Count | Percentage |
|----------------|-------|------------|
| Fairly Priced  | 37    | 68.5%      |
| Over Priced    | 17    | 31.5%      |

### Rating Distribution
| Rating | Count |
|--------|-------|
| ★★★★★  | 25    |
| ★★★★   | 15    |
| ★★★    | 12    |
| ★★     | 8     |
| ★      | 5     |

## Statistical Analysis

### Test 1: Pricing vs Rating
**Null Hypothesis (H₀):** Rating is independent of pricing  
**Result:** Significant (p < 0.05)  
**Conclusion:** Pricing strategy affects customer ratings

### Test 2: Previous Orders vs Best Place
**Null Hypothesis (H₀):** No association between variables  
**Result:** Significant (p < 0.05)  
**Conclusion:** Past purchases influence "best place" perception

## Technical Implementation

### Data Cleaning
```python
# Clean whitespace and remove duplicates
df['Previous Order'] = df['Previous Order'].str.strip()
df = df.dropna()
