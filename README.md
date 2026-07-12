# Candy Power Ranking — New Product Case Study

# 1. Business question
The purchasing team wants a data-driven view on **which candy characteristics drive
customer sentiment (winpercent)**, to decide whether the new store-brand product should be
**cookie-based** or a **gummy**, and what it should contain (chocolate, caramel, fruity,
peanut/almond, sugar level, price point, format, etc.).

## 2. Data
Source: FiveThirtyEight "Ultimate Halloween Candy Power Ranking"
https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking

- 85 candies, 12 features + `winpercent` (target)
- `winpercent` = share of ~269,000 pairwise head-to-head matchups won (higher = more preferred)
- 9 binary attributes (chocolate, fruity, caramel, peanutyalmondy, nougat,
  crispedricewafer, hard, bar, pluribus) + sugarpercent, pricepercent (both percentile-scaled)
- No missing values, no duplicate candies.
