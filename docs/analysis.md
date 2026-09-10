# Analysis: Apocalypse Sales Dashboard

## 1. Business Problem
The dataset simulates sales for four prepper stores selling survival products. The goal is to understand:
- Which products sell best
- Which customers contribute the most
- How sales are distributed geographically
- How customer purchasing behavior differs
- How price and production cost relate to sales

## 2. Data Overview

| Table | Description |
|---|---|
| Apocolypse Store | 10 products with price and production cost |
| Apocolypse Sales | 75 sales transactions with customer, product, units sold, and date |
| Customer Information | 4 customers with address and state |
| Customer Buyer Information | 50 buyer records with total purchased, state, and age |

- Time range: January 2022 – March 2022
- Total units sold: 3000+
- Products: 10
- Customers: 4

## 3. Key Findings

### 3.1 Product Sales Ranking

| Product | Units Sold |
|---|---|
| Multitool Survival Knife | 477 |
| Nylon Rope | 390 |
| Duct Tape | 365 |
| Stainless Steel Axe | 350 |
| N95 Mask | 343 |
| Weatherproof Jacket | 265 |
| Water Purifier | 227 |
| Backpack | 212 |
| Waterproof Matches | 190 |

**Insight:** Multitool Survival Knife, Nylon Rope, and Duct Tape are the top three products. These are core survival items, suggesting customers prioritize essential tools.

### 3.2 Customer Sales Ranking

| Customer | Total Units |
|---|---|
| Uncle Joe's Prep Shop | 951 |
| Apocolypse Preppers United | 828 |
| Alex The Analyst Apocolypse Preppers | 613 |
| Prep4Anything Prepping Store | 609 |

**Insight:** Uncle Joe's Prep Shop is the largest customer. Retention and inventory priority should focus on this account.

### 3.3 Geographic Distribution

| State | Share |
|---|---|
| MN | 28.14% |
| DE | 17.57% |
| NC | 12.41% |
| IL | 10.40% |
| NY | 7.72% |
| FL | 5.63% |
| TX | 12.40% |
| MI | 5.60% |

**Insight:** MN, DE, and NC together account for over 58% of units purchased. Sales are concentrated in a few states.

### 3.4 Customer Purchase Patterns

From the 100% stacked bar chart:
- Uncle Joe's Prep Shop: N95 Mask 22.08%, Multitool Survival Knife 17.03%
- Apocolypse Preppers United: Multitool Survival Knife 26.69%, N95 Mask 24.15%
- Alex The Analyst Apocolypse Preppers: N95 Mask 31.00%, Multitool Survival Knife 19.25%
- Prep4Anything Prepping Store: N95 Mask 39.57%, Multitool Survival Knife 22.17%

**Insight:** Different customers have different product preferences. Prep4Anything and Alex The Analyst prefer N95 Masks, while Apocolypse Preppers United prefers Multitool Survival Knives.

### 3.5 Sales Trend

- January: high sales for Multitool Survival Knife and Duct Tape
- February: relatively stable across products
- March: Nylon Rope dropped sharply; other products also declined

**Insight:** Sales peaked in January–February and declined in March. This may be seasonal, but with only three months of data, no long-term conclusion can be drawn.

### 3.6 Price and Production Cost

| Product | Price | Production Cost |
|---|---|---|
| Weatherproof Jacket | 79.99 | 30.59 |
| Stainless Steel Axe | 45.50 | 32.45 |
| Backpack | 39.99 | 26.92 |
| Nylon Rope | 30.99 | 13.67 |
| Water Purifier | 30.25 | 17.93 |
| Multitool Survival Knife | 28.99 | 10.58 |
| Solar Battery Flashlight | 26.49 | 13.41 |
| Waterproof Matches | 7.99 | 2.89 |
| Duct Tape | 6.25 | 4.87 |
| N95 Mask | 2.75 | 1.01 |

**Insight:** Higher price does not always mean higher sales. Weatherproof Jacket has the highest price but only 265 units sold. N95 Mask has the lowest price and sold 343 units.

### 3.7 Gross Margin Estimate

Gross margin = (Price − Production Cost) / Price

| Product | Gross Margin |
|---|---|
| Multitool Survival Knife | 63.5% |
| Waterproof Matches | 63.8% |
| N95 Mask | 63.3% |
| Nylon Rope | 55.9% |
| Water Purifier | 40.7% |
| Solar Battery Flashlight | 49.4% |
| Backpack | 32.7% |
| Stainless Steel Axe | 28.7% |
| Weatherproof Jacket | 61.8% |
| Duct Tape | 22.1% |

**Insight:** Multitool Survival Knife, N95 Mask, and Waterproof Matches have both high margin and solid sales. Duct Tape has high sales but low margin, functioning as a traffic driver rather than a profit driver.

## 4. Business Recommendations
1. Prioritize inventory for Multitool Survival Knife, Nylon Rope, and Duct Tape.
2. Focus retention efforts on Uncle Joe's Prep Shop.
3. Increase marketing and distribution in MN, DE, and NC.
4. Tailor product recommendations by customer segment.
5. Investigate the March sales decline.
6. Review pricing or cost structure for low-margin products such as Duct Tape.
