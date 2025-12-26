# E-Commerce_Analysis

<h2 align="center"> Overview </h2>

This report represents an in-depth analysis of a global e-commerce businesss specializing in popular gaming products. The available data contains approximately 22,000 transactions from 18,000 customers, covering the period from January 2019 to February 2021.

The analysis will primarily focus on the 2019 - 2020 period to providing a clearer view of business performance before and during a major shift in global consumer behavior. The objective is to examine sales trends, product performance, and marketing effectiveness in order to identify key revenue drivers, uncover growth opportunities, and understand changes in customer purchasing behavior over time.

The key insights and recommendations of this analysis are structured around the following areas:

- General Sales Trends:
  - Analyze overall performance using key metrics such as total revenue, order volume, and average order value (AOV) to understand demand patterns and year-over-year changes.
- Product Performance:
  - Identify top products that contribute the most to the total revenue and assess their relative impacts on the overall performance of the business.
- Market Share by Region:
  - Evaluate regional contributions to sales, highlighting core revenue-driving markets as well as underperforming regions but show potential investment opportunities.
- Marketing Channels Effectiveness:
  - Evaluate the effectiveness of the business's marketing strategies by analyzing customer acquisition across different channels and identifying which channels contribute most to sales.

**Research Question:**

How do sales performance and marketing effectiveness vary by year, product, region, and channel, and what factors drive changes in revenue and order volume over time?

<h2 align="center"> Data Overview </h2>

<table style="width:100%" align="center">
  <tr>
    <th>Dataset</th>
    <th>Coverage</th>
    <th>Key features</th>
  </tr>

  <tr>
    <td>Gamezone Orders Data</td>
    <td>01/2019 - 02/2021</td>
    <td>Purchase Timestamp, Product, Price, Country, Marketing Channels</td>
  </tr>

  <tr>
    <td>Region</td>
    <td></td>
    <td>Country, Region</td>
  </tr>
</table>

<h2 align="center"> Executive Summary </h2>

This analysis reveals several key patterns in sales and marketing performance:

1. **Sales Growth Accelerated Sharply in 2020, Followed by Early Signs of Decline**

   - Total revenue increased significantly in 2020, reaching $4.07M, representing a 164% year-over-year (YoY) growth.
   - The strongest performance occurred between September and December 2020, with December marking the peak month ($559K).
   - Despite strong annual growth, sales exhibited notable volatility, including a sharp decline in October 2020 and a continued downward trend in early 2021, suggesting that growth momentum may not be sustained without intervention.
  
2. **Revenue Is Highly Concentrated Among Top Products:**

   - A small group of products consistently generated the majority of revenue across both years.
   - This concentration reflects strong product–market fit for core offerings but also introduces dependency risk, as overall performance is heavily influenced by a limited product portfolio.

3. **Sales Trends Are Strongly Influenced by Global and Seasonal Factors:**

   - All regions and products experienced a pronounced decline in late 2019, followed by a sharp increase throughout 2020.
   - This synchronized pattern across markets suggests a macro-level impact, potentially related to shifts in consumer behavior during the COVID-19 period.
   - Seasonal effects are evident, with recurring peaks in September and December in both years, likely driven by promotional cycles and holiday demand, while October consistently underperformed across years.

4. **Marketing Channel Effectiveness Does Not Vary:**

   - Direct traffic dominates sales performance, contributing approximately 70–80% of total revenue.
   - Other channels (email, social media, affiliate) contribute minimally, indicating inefficient channel diversification and potential underinvestment or ineffective execution outside the direct channel.

<h2 align="center"> Insight Deep Dive & Visualizations </h2>

### 💰 Sales Trends

- Sales revenue increased sharply in early 2020, with April 2020 recording over 220% growth compared to January 2020 (from $109K to $351K), and nearly 190% growth compared to April 2019, highlighting a major sale anomaly in just 1 year.
- Despite this surge, monthly sales patterns reveal strong volatility, with recurring declines before and after seasonal peaks.
- The sharp revenue drop observed in January 2021 (~47%), followed by further decline in February, suggests potential demand saturation or weakening consumer engagement entering 2021.

### Average Order Value (AOV) and Number of Orders

- AOV showed considerable fluctuation over the analyzed period, with lowest level in January 2019 (~$214) and reached its highest level in December 2020 ($329)
- There was a sharp increase in early 2020 (+36% in January), aligning with the outbreak of COVID-19 which might affect the ecommerce market, however it did not consistently translate into higher revenue but instead followed by continuous instability the following period.
- Analysis indicates that declines in order volume, rather than AOV, were the primary driver of revenue downturns. Order count and total revenue closely mirror each other across both years, emphasizing that decline in revenue primarily due to fewer orders rather than the fluctuation in AOV or price of the products.

### Product Performance by Year

- Revenue concentration is extreme: four products—Gaming Monitor, Nintendo Switch, PlayStation, and Ideapad Gaming - account for approximately 97% of total revenue across both years.
- Several products show minimal or inconsistent sales activity, contributing negligibly to overall performance.
- The Gaming Headset exhibited persistently weak performance, with no recorded sales in multiple months, indicating poor product-market fit, ineffective promotion, or missing sales data.
- products aov:

### Market Share by Region

- North America dominates sales, contributing over 50% of total revenue in both years, while Latin America consistently contributes the smallest share (~5%), indicating limited market penetration.
- All regions experienced similar sales patterns - sharp decline in early 2020 followed by strong recovery - supporting the presence of a global demand shock, which potentially caused by the outbreak of COVID-19 pandemic.
- While most regions showed improvement toward the end of 2020, Asia-Pacific was the only region exhibiting continued growth in early 2021. This pattern combined with a slight shift in the market share in 2020 highlights a potential emerging opportunity.

### 📈 Marketing Channels Effectiveness

- Direct purchases account for the vast majority of revenue (70–80%), while all other channels contribute marginally.
- This heavy reliance on direct traffic is atypical for mature e-commerce operations and suggests underutilization or inefficiency in marketing strategies.
- Email shows modest growth potential, while social media and affiliate channels appear underdeveloped rather than ineffective, indicating opportunities for strategic experimentation and optimization.

<h2 align="center"> Conclusion </h2>

### Key Takeaways

- Revenue growth in 2020 was driven primarily by increased order volume, not sustained improvements in AOV.
- Sales performance is highly dependent on a narrow set of products, increasing exposure to product-level risk.
- Regional demand patterns suggest both mature markets and emerging growth opportunities.
- Marketing performance is constrained by over-reliance on direct traffic and limited channel diversification.

### Business Implications

- Sustainable growth requires balancing volume growth, product diversification, and channel optimization.
- Improving demand generation through diversified marketing channels is critical to reducing revenue volatility.
- Strategic focus should shift from short-term revenue spikes to stable, repeatable growth drivers.

<h2 align="center"> Recommendations </h2>

- Rationalize the product portfolio by discontinuing or repositioning persistently underperforming products.
- Reduce over-reliance on direct traffic by strengthening email, social media, and affiliate strategies through targeted campaigns and experimentation. Email shows a potential improve so this can be a method that marketing team can focus on. Although social media and affeliate show much lower contribution, I think that these 2 channels are also potential since as a customer I found myself most of the time discovering products through these 2 channels.
- Double down on high-performing regions while investing selectively in regions showing emerging growth, particularly Asia-Pacific.
- Align promotional strategies more closely with proven seasonal demand patterns while mitigating recurring low-performance periods (e.g., October).

<h2 align="center"> Limitations & Potential Improvements </h2>

**Limitations:**

- Marketing spending data is not available (ROI analysis not possible)
- Cost data is not avaialble to evaluate profit
- Lack real-time feedback and guidance from stakeholders to provide clearer insights and recommendations

**Future Works:**

- Integrating marketing cost to evaluate ROI
- Performing customer cohort and retention analysis
- Including profitability & margin trends (if available)
- Building simple predictive models for sales forecasting
