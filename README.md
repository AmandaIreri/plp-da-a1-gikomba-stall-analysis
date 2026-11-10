# Gikomba Market Stall Performance Analysis

**Name:** Amanda Ireri
**Cohort:** 1 Million Devs, Data Analysis with Python

## Business problem

Wanjiku runs a fresh-produce stall at Gikomba Market. For two weeks, she has written her daily sales in a notebook and kept a rough record of stock, but she doesn't know how the business is really doing. She wants to know whether sales are growing, which days matter most, which products she should restock, and where to focus her effort. I analysed her 14 days of sales (KES 46,450 in total) and her five-product stock register using core Python only, with no pandas or NumPy.

**How to run:** [Open in Colab](https://colab.research.google.com/github/AmandaIreri/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb)

Click the badge, then choose **Runtime → Run all**.

## Top three findings

1. **Weekends are far stronger than weekdays.** Weekends average KES 4,900 a day against KES 2,685 on weekdays, which is 82.5% higher.
2. **The business is growing.** Sales rose 10.7% from week 1 (KES 22,050) to week 2 (KES 24,400).
3. **Two products need restocking now, and Avocado is the profit leader.** Tomatoes (18 kg vs reorder level 25 kg) and Sukuma (9 kg vs 15 kg) are below their reorder levels. Avocado has the highest gross margin at 42.9%.
