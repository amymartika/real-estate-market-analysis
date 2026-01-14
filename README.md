# Real Estate Market Analysis
Top marktes of oppotunity for a growing real estate company. 

* **Tools:** SQL (MySQL & Workbench)

## Table of Contents

1. Project Background
2. Data Collection
3. Executive Summary
4. Recommendations

### Project Background
Glo Real Estate is a growing real estate company that's just gone national. They operate in 50 markets with 1,000 agents across the nation. When a house sells, the selling agent earns 2% of the home's value and Glo Real Estate earns 1% of the home's value. 

The marketing manager has asked for an analysis to identify the 5 best markets for Glo Real Estate. They've provided data on 14,000 transactions and 50,000 cusotmers from 2025 and are hoping to better understand the company's performance in these markets. The marketing team will use these insights to shape their marketing strategy for 2026 with the specific goal of increasing the company's revenue from its 2025 revenue of $69M.

Insights and recommendations are provided in the following key areas: 

Links: 
* View the SQL queries performed here. 

### Data Collection

### Executive Summary
Of the 50 markets sampled, Glo Real Estate performs well in 9 markets based on recent pricing increase trends, median days on market (DOM), and closing price vs listing price. **Glo Real Estate holds at least 12% of market share in 3 of these markets.** If our marketing team can **concentrate on increasing market share in 6 key cities**, we've identified a potential revenue increase from **$69M in 2025** to **$94M in 2026,** before factoring in organic growth in these markets YoY.

#### Overview of Findings
Glo's top 5 markets are those that have the highest demand, which is indicated by 3 key factors: 
* **Percent of homes that saw a pricing increase in the last 30 days.** In each market, 0 to 9% of homes on the market had a listing price increase. Markets with a higher percentage were ranked higher.
* * **Median days on market (DOM):** Markets saw a range of 12 days to 92 days on the market. Markets with a lower DOM were rnaked higher.
* **Avg percent increase in closing price vs listing price:** Closing prices in each market ranged from 10% below the list price to 16% above hte list price. Markets with a higher percent increase were ranked higher.

After creating a market rating for each of our markets, we then compared our sales data against the strongest-performing markets (60th percentile and up), looking at 2 key factors: 
* **Percent above the market's median price that our homes sell for.** Of the markets performing above average, our homes sell anywhere from 71% below the market median up to 197% of the market median.
* **Our share of listings compared to the total number of listings.** Of the markets performing above average, we have anywhere from 3% to 19% share of the total listings on the market.

This methodology presents a strong case for our top 5 markets: 
1. **Buffalo, NY** - We have 19% market share of listings and our homes sell for 66% above the market median.
2. **Grand Rapids, MI** - We have 16% market share of listings and our homes sell for 40% above the market median.
3. **Fresno, CA** - We have 12% market share of listings and our homes sell for 11% above the market median.
4. **Richmond, VA** - We have 9% market share of listings and our homes sell for 25% above the market median.
5. **Virginia Beach, VA** - We have 6% market share of listings and our homes sell for 32% above the market median. 

#### Market Trends
Smaller markets are trending toward favoring sellers, while larger markets are trending toward favoring buyers. 
* **8 out of 10 markets** with the highest population **ranked below the average in the market,** largely due to long median DOM ranging from 44 to 92 days - compared to the average of 46 days.
* **Houston, TX and Washington, DC are the only two markets in the top 10 population that rank average across the market** for demand. For Houston, this is due to 4% of homes seeing a price increase in the last 30 days, compared to the market average of 2%. For Washington, DC, this is due to homes sitting on the market for 45 days (in line with the average) and selling for just 1% below list price (compared to the average of 2% below).
* Meanwhile, **7 out of 10 of the markets with the highest demand have a population below the average of 3.7M.** These homes are consistently seeing price increases and low DOM, but the sell price ranges from 5% below listing to 16% above listing. 

### Recommendations
In evaluating the top 5 markets for Glo in 2025, we uncovered 4 opportunity marktes to focus on in 2026: 

1. Balitmore, MD
2. Kansas City, MO
3. Minneapolis, MN
4. Detroit, MI

These 4 markets all perform above average in our market rating, and we consistently sell homes above the median in the area. Meanwhile, we only have 3-4% of market share in these cities, compared to our 6-19% market share in our top markets (avg of 12%). 

If Glo's marketing team can concentrate marketing efforts in these 4 markets with the goal of increasing share of market to 12%, we could expect the following impacts to 2026 revenue: 

* **Baltiomre, MD** reveunue could increase from **$1.4M** in 2025 to **$4.0M** in 2026.
* **Kansas City, MO** revenue could increase from **$1.4M** in 2025 to **$3.9M** in 2026.
* **Minneapolis, MN** revenue could increase from **$1.4M** in 2025 to **$5.2M** in 2026.
* **Detroit, MI** revenue could increase from **$1.7M** in 2025 to **$7.9M** in 2026.
* **Total revenue could increase from $5.9M in 2025 to $21M in 2026, up 22% from 2025.**

Potential next steps: 
* Compare seasonal trends in our opportunity markets against national averages to identify any 
* Segment customers in our opportunity markets to identify key demographics to target in our marketing efforts.
