---

# Inflation Pulse India CPI Tracker National Macroeconomy Analysis (2013-23)

---

## 🎯 Objective

To develop a structured, visual, and data-driven analysis of India’s Consumer Price Index (CPI) to uncover actionable insights that support economic decision-making at both policy and strategic levels.

Project Purpose:
Identify key contributors to inflation by analyzing category-wise CPI weights and index changes.
Evaluate historical and recent inflation trends, both year-on-year and month-on-month.
Assess the impact of major global and domestic events—such as COVID-19 and international oil-price fluctuations—on India’s inflation dynamics.
Create an interactive dashboard that transforms complex CPI data into clear visuals for policymakers, economic strategists, and data analysts.

Key KPIs:
Overall CPI inflation trend (annual & monthly)
Category-wise inflation contribution
Pre- vs Post-COVID inflation shifts
Correlation of crude oil prices with fuel & food inflation

Deliverables:
Excel dashboard
Presentation slides summarizing insights
Concise analytical report
---


---

## 📘 Project Overview

Context Highlights:

Focuses on India’s Consumer Price Index (CPI) to analyze key inflation drivers and sectoral trends.

Incorporates monthly CPI data across major categories — Food, Fuel, Housing, Health, Education, etc.

Integrates macro-economic indicators such as global crude oil prices and COVID-19 impact periods for contextual depth.

Utilizes Microsoft Excel (Pivot Tables, Charts, KPIs) and optionally Power BI for visual storytelling.

The Inflation Insights Dashboard enables:
Year-over-year and category-based inflation trend analysis
Comparison of food vs. non-food inflation contribution
Assessment of COVID-19 and oil price shocks
Exploration of correlation between fuel prices and CPI inflation

Aids policymakers, analysts, and businesses in monitoring inflation and framing data-driven economic strategies.

---

## 🗂️ Data Overview & Schema

Data Source:
Source: National Statistical Office (NSO), Ministry of Statistics & Program Implementation (MoSPI), Government of India
Data Type: Official monthly Consumer Price Index (CPI) datasets.
Time Period: January 2013 – December 2023 (11 years of monthly observations).
Supplementary Data: Monthly global crude-oil prices (Brent/Indian Basket) from Petroleum Planning & Analysis Cell (PPAC), Government of India

Data Structure & Metrics:
Key Index Types: CPI–Rural (CPI-R), CPI–Urban (CPI-U), CPI–Combined (General).
Categories: The dataset includes 20+ CPI sub-groups aggregated into broader buckets: Food & Beverages, Fuel & Light, Housing, Clothing & Footwear, Transport, Healthcare, and Miscellaneous.
Calculated Metrics: Year-on-Year (YoY) inflation %, Month-on-Month (MoM) % change, pre/post-COVID comparisons, and correlation matrices.


## 💻 Tech Stack

Tools:
Microsoft Excel 
Data cleaning & preprocessing
Pivot Tables for aggregation
Pivot Charts for visualizations
Dashboard creation

PowerPoint 
Presentation and final dashboard snapshots

---
## 📈  Methodology & Analysis

Approach:
Grouped detailed subcategories (e.g., Cereals, Beverages, Milk) into broader economic buckets like Food, Clothing & Footwear, Energy, Health etc.
Computed Year-on-Year (YoY) and Month-on-Month (MoM) inflation rates
Calculated percentage contributions of each bucket based on their index values, ensured the total adds up to 100%, reflecting each category’s proportional impact on the CPI index
Conducted correlation analysis using =CORREL() (e.g., imported oil prices vs. CPI categories)
Compared Pre- vs. Post-COVID inflation trends (cutoff: Mar 2020)
Handled missing values with a 3-month moving-average technique
Line, bar, and pie charts for trend and category insights
Slicers/filters for interactivity

Key Excel functions: =IF(), =AVERAGE(), custom %-change formulasData Preparation & Processing:
Data Cleaning: Missing observations handled and imputed with 3-month moving averages.
Aggregation: Detailed subcategories were aggregated into broader economic buckets (Food, Energy, Essentials) for macro-analysis.

--- 
## ❓ Problem Statements

Key Questions⁠:CPI Category Contribution
Based on the latest month's data, identify the contribution of different broader categories (food, energy, health etc.) towards the CPI basket. 
 ⁠Which broader category has the highest contribution towards CPI calculation. 
 Contribution is calculated by evaluating the underlying index values for broader category and should add to 100% when contribution from different broader categories are added.
Y-O-Y CPI Inflation Trends
A trend of Year-on-Year increase in CPI (rural + urban) inflation starting 2017 for the entire basket of products combined.
 ⁠Create a graph depicting the growth rate Y-o-Y and identify the year with highest inflation rate.
 ⁠Highlight the reason why the year has the highest inflation.

M-o-M Food Inflation Trend (Jun’22 – May’23)
With India's retail inflation reaching a 3-month high of 5.55% in November 2023, largely due to a sharp rise in food prices. Analyze the following for 12 months ending May'23.
  ⁠Investigate trends in the prices of broader food bucket category and evaluate month-on-month changes. Highlight month with highest and lowest food inflation
  ⁠Identify the absolute changes in inflation over the same 12 months period and identify the biggest individual category contributor (only within broader food category) towards inflation

COVID-19 Impact on CPI Inflation (Pre vs. Post Mar’20)
Investigate how the onset and progression of the COVID-19 pandemic affected inflation rates in India. Analyze the Impact of key pandemic milestone (first lockdown) on the CPI inflation %, specially focus on categories like healthcare, food, and essential services.
Impact of Imported Oil Price Fluctuations on CPI (2021–23)
Investigate how major global economic events (like imported crude oil price fluctuations) have influenced India's inflation. This can include an analysis of imported goods and their price trends.
•  ⁠For the purpose of this analysis, focus only on the imported oil price fluctuations for years 2021 to 2023 (month-on-month)
•  ⁠Identify trends in oil price change with change in inflation prices of all the categories and identify category whose inflation prices strongly changes with fluctuations in imported oil price 

---
## 💡Key Insights

Top Findings:
Food & Beverages consistently emerged as the largest contributor to inflation (avg. ~45% weight in CPI).

Fuel & Light showed the highest volatility, strongly correlated (r ≈ 0.82) with global crude oil prices.

Post-COVID (2020–2022) period saw a shift in inflation drivers — essentials (Food, Health) surged, while discretionary categories (Clothing, Recreation) stabilized.

Urban inflation outpaced rural inflation post-2021, mainly due to housing and service cost escalation.

Headline inflation breached the RBI tolerance band (6%) multiple times, reflecting persistent supply shocks.

Correlation analysis confirmed that fuel price hikes ripple into food inflation, indicating strong cost-push effects.


Supporting Metrics:
YoY CPI growth: 6.4% (avg.) during 2020–23

Max inflation: 7.8% in 2022 (Fuel & Light)

Correlation (Oil vs CPI): r = 0.82

---
## 📍Conclusion

Summary:
Food inflation remains the primary driver of India’s overall CPI due to its nearly 50% weight — making supply-side stability critical.

2022 inflation peaks exposed vulnerabilities in supply chain resilience and dependency on global commodities, especially fuel and food.

Month-on-month volatility in essentials directly impacts lower-income households, emphasizing the need for:
Real-time agricultural price monitoring
Timely policy interventions (MSP, stock release)
Strengthened logistics and distribution systems

Inflation management requires forward-looking preparedness — governments must anticipate lagged inflation spikes post-crisis and ensure stability in core consumer categories (food, healthcare, housing).

Oil price fluctuations have a cascading impact across sectors; hence, fuel policy calibration (subsidies, tax control) and global oil monitoring are vital for macroeconomic stability.

For businesses and investors, tracking CPI-linked sectors (FMCG, logistics, energy) can guide smarter pricing and risk management decisions.

---

## ✅ Business Impact & Use Cases

Government & Policy Bodies:Enable data-backed decisions on price stabilization, subsidy allocation, and inflation control measures.

Economic Planners & Analysts:Leverage CPI insights to forecast inflation trends, assess sectoral pressures, and design monetary responses.

Investors & Financial Institutions:Use category-level CPI and oil-price correlations to anticipate market volatility and optimize commodity investment strategies.

General Public & Businesses:Enhance awareness of cost-of-living shifts and guide budget planning or pricing strategies in inflation-sensitive sectors.

---

## 📌 Data Methodology & Calculations

* **Monthly Inflation:**

    Monthly Inflation Rate = ((CPI_current_month − CPI_previous_month) / CPI_previous_month) × 100
  
 * **Annual Inflation:**

    Yearly Inflation Rate = ((CPI_current_year − CPI_previous_year) / CPI_previous_year) × 100
 
* **Correlation Coefficient (Excel):**
  `=CORREL(range1, range2)` to assess external price shocks (e.g., oil)

---

## 🙏 Acknowledgements

Project Analyst: Anik Chakraborty		
📧 Email: anikc1710@gmail.com

Special Thanks To:
National Statistical Office (NSO) – for CPI data
Petroleum Planning & Analysis Cell (PPAC) – for crude oil price data
Coding Ninjas – for project framework and guidance
