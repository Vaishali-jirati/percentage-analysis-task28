# Simple Percentage Analysis (Superstore Dataset)

## Overview
Calculated how much each product category contributes to total sales and total profit in the
Sample Superstore Orders data (10,194 order lines), with a percentage table and charts.

## Workbook structure
- Data: original Orders data
- Summary: percentage table, two pie charts and findings

## Method
- SUMIFS: total sales and total profit per category
- % of Total Sales = category sales / total sales
- % of Total Profit = category profit / total profit
- The denominator is fixed with $ (for example $B$5), so each percentage uses the same total
- Check: the percentages add up to 100.00%

## Results
| Category | Sales | % of Total Sales | Profit | % of Total Profit |
|---|---|---|---|---|
| Furniture | 754,747.76 | 32.44% | 19,730.00 | 6.75% |
| Office Supplies | 731,893.31 | 31.46% | 126,023.44 | 43.11% |
| Technology | 839,893.28 | 36.10% | 146,543.38 | 50.14% |
| Total | 2,326,534.35 | 100.00% | 292,296.81 | 100.00% |

## Denominators
- % of Total Sales = category sales / total sales (2,326,534.35)
- % of Total Profit = category profit / total profit (292,296.81)

## Tools Used
Microsoft Excel (SUMIFS, percentage formulas, pie charts)

## Dataset
Sample Superstore Dataset
