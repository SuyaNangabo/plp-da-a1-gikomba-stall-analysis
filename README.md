# Wanjiku's Stall Performance Analysis
**Name:** Brenda Suya Nangabo

**Cohort:** 1Million Devs for Africa program

# Wanjiku's Business Problem
Wanjiku runs a fresh-produce stall at Gikomba Market and has spent two weeks recording her daily sales by hand in a notebook, alongside a rough record of her stock. She has no clear picture of how the business is performing, so she has hired me as a freelance data analyst to answer four questions: how is the business doing overall, is it growing from week one to week two, what should she restock, and where should she focus her effort. The data covers 14 days of sales in KES and five products (tomatoes, onions, sukuma, potatoes and avocado), each with quantity in stock, reorder level, cost and selling price. My job is to turn those figures into specific, number-backed recommendations, so she can decide quickly which days to prioritise, which low-stock items to reorder, and which products earn the best margins. I am using core python only.

## How to Run

Open the notebook in Google Colab: [![Open In Colab]

# My top findings
1. Her business is a weekend business.
Weekends average KES 4,900 a day against KES 2,685 on weekdays, which is 82.5% more. Saturdays alone (2 of 14 days) bring in KES 10,800, or 23% of all sales. This is the most important finding because it tells her where stock, time and energy should go. A stockout on a Saturday costs far more than one on a Tuesday.

**2. The growth is real, not a lucky spike.**
Sales rose 10.7% week-on-week, but what makes it convincing is that all 7 days were higher in week 2 than in week 1. Weekdays grew about 10.6% and weekends about 10.8%, so the whole stall is moving up together, not just one good day. That gives her something concrete to say: “the business is healthier than it was two weeks ago.”

**3. Her stock doesn’t match where her money is made.**

Tomatoes (18 kg vs 25 kg) and sukuma (9 kg vs 15 kg) are below their reorder levels going into her strongest days.
Avocado has her best margin (42.9%) but only 2 kg of headroom above its reorder level.
Onions (lowest margin, 30%) hold twice their reorder level, and potatoes hold 55 kg against a 30 kg level, so cash is sitting in slower, lower-margin stock.

The fix costs little, because the shortfalls are only 7 kg and 6 kg. Shifting purchases from onions and potatoes to tomatoes, sukuma and avocado puts the money where it earns more.

**Two honest limits:** two weeks is a short window, so the 10.7% growth could shift with more data. And the stock table has no sales per product, so I can say avocado has the best margin per shilling, but not that it earns the most total profit.

