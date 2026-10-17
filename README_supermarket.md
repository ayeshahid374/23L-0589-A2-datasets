# Supermarket Sales - Cleaned Dataset

File: 23L_0589_A2_supermarket_cleaned.csv
Version: v1.0
Date: 18 October 2026
Author: Ayesha Shahid (23L-0589)

## Original source
Supermarket Sales file provided by the instructor (supermarket_Sales.csv).

## What I changed
- No missing values, duplicates or wrong labels were found, so nothing was removed.
- Column names were changed to short names (for example Customer stratification rating is now rating).
- date was converted to datetime.
- 9 outliers in total were kept.
- Tax, total, cogs, income and margin were kept, but they are calculated from price and quantity.
- 1,000 rows.

## New columns
hour, weekday, month
