# Inflation Pulse India CPI Tracker National Macroeconomy Analysis (2013-23)

---

## 🎯 Objective

To develop a **structured, visual, and data-driven analysis** of India’s Consumer Price Index (CPI) to uncover actionable insights that support **economic decision-making** at both policy and strategic levels.

**Project Purpose:**

* Identify key contributors to inflation by analyzing **category-wise CPI weights** and **index changes**.
* Evaluate **historical and recent inflation trends**, both Year-on-Year (YoY) and Month-on-Month (MoM).
* Assess the impact of **major global and domestic events**—such as COVID-19 and international oil-price fluctuations—on India’s inflation dynamics.
* Create an **interactive dashboard** that transforms complex CPI data into clear visuals for policymakers, strategists, and analysts.

**Key KPIs:**

* Overall CPI inflation trend (annual & monthly)
* Category-wise inflation contribution
* Pre- vs. Post-COVID inflation shifts
* Correlation of crude oil prices with fuel & food inflation

**Deliverables:**

* Excel dashboard
* Presentation slides summarizing insights
* Concise analytical report

---

## 📘 Project Overview

### **Context Highlights:**

* Focuses on **India’s Consumer Price Index (CPI)** to analyze key inflation drivers and sectoral trends.
* Incorporates **monthly CPI data** across major categories — *Food, Fuel, Housing, Health, Education,* etc.
* Integrates **macro-economic indicators** such as *global crude oil prices* and *COVID-19 impact periods* for contextual depth.
* Utilizes **Microsoft Excel** (Pivot Tables, Charts, KPIs) and optionally Power BI for visual storytelling.
* The **Inflation Insights Dashboard** enables:

  * Year-over-year and category-based inflation trend analysis
  * Comparison of food vs. non-food inflation contribution
  * Assessment of COVID-19 and oil price shocks
  * Exploration of correlation between fuel prices and CPI inflation
* Aids **policymakers, analysts, and businesses** in monitoring inflation and framing **data-driven economic strategies**.

---

## 🗂️ Data Overview & Schema

**Data Source:**

* **Primary:** National Statistical Office (NSO), Ministry of Statistics & Programme Implementation (MoSPI), Government of India
* **Supplementary:** Monthly crude oil prices (Brent/Indian Basket) from Petroleum Planning & Analysis Cell (PPAC), Govt. of India

**Time Period:** January 2013 – December 2023 (11 years, monthly frequency)

**Data Structure & Metrics:**

* **Index Types:** CPI–Rural (CPI-R), CPI–Urban (CPI-U), CPI–Combined (General)
* **Categories:** 20+ CPI sub-groups aggregated into broader buckets — *Food & Beverages, Fuel & Light, Housing, Clothing & Footwear, Transport, Healthcare, Miscellaneous*
* **Calculated Metrics:** YoY inflation %, MoM % change, pre/post-COVID comparisons, correlation matrices

---

## 💻 Tech Stack

**Tools:**

* **Microsoft Excel:** Data cleaning, preprocessing, analysis, visualization, and dashboard creation
* **PowerPoint:** Presentation and final dashboard snapshots

---

## 📈 Methodology & Analysis
**Preparation, Process & Analytical Approach:**
  * Grouped detailed subcategories (e.g., **Cereals, Beverages, Milk**) into broader economic buckets such as **Food, Clothing &     Footwear, Energy, Health**, etc. for comprehensive analysis.

  * Computed **Year-on-Year (YoY) and Month-on-Month (MoM) inflation rates** using CPI index values

  * Calculated percentage contribution of each category to total CPI, ensuring **all weights sum to 100%**, reflecting each segment’s proportional impact.

  * Conducted **correlation analysis using `=CORREL()`** (e.g., imported oil prices vs. CPI categories).

  * Compared **Pre- vs. Post-COVID** inflation patterns (cutoff: March 2020).

  * Performed **data cleaning and imputation** for missing values using a **3-month moving average** technique.

  * Created **line, bar, and pie charts** to visualize category trends and inflation dynamics.

  * Utilized key Excel functions like **`=IF()`, `=AVERAGE()` and custom percentage-change** formulas for calculations and automation.


---

## ❓ Problem Statements

**Key Questions:**

* **1. CPI Category Contribution**

  *  Identify contribution of major CPI categories (Food, Energy, Health, etc.)
  *  Determine which category has the **highest weight** in CPI composition

* **2. Year-on-Year CPI Inflation Trends**

  *  Analyze YoY inflation (Rural + Urban) since 2017
  *  Identify the **year with highest inflation rate** and reasons behind it

* **3. Month-on-Month Food Inflation (Jun’22 – May’23)**

  *  Study 12-month food inflation trajectory
  *  Highlight months with **highest and lowest food inflation**
  *  Determine the **biggest contributor** within the Food category

* **4. COVID-19 Impact on CPI (Pre vs. Post Mar’20)**

  *  Compare inflation before and after pandemic onset
  *  Focus on Healthcare, Food, and Essential Services inflation

* **5. Oil Price Fluctuations vs. CPI (2021–23)**

  *  Analyze how **crude oil price movements** affected India’s CPI
  *  Identify **CPI categories** most responsive to oil price changes

---

## 💡 Key Insights

**Top Findings:**

* *Food & Beverages* consistently the largest inflation driver (~45% CPI weight).
* *Fuel & Light* exhibited highest volatility, correlated with oil prices (**r ≈ 0.82**).
* Post-COVID era (2020–22) saw **essentials inflation surge**, discretionary items stabilize.
* Urban inflation overtook rural inflation post-2021 due to **housing and services**.
* Headline CPI exceeded **RBI’s 6% tolerance band** multiple times, reflecting supply shocks.
* Fuel price spikes showed **ripple effects on food inflation**, highlighting cost-push dynamics.

**Supporting Metrics:**

* Avg. YoY CPI growth (2020–23): **6.4%**
* Max inflation: **7.8% (Fuel & Light, 2022)**
* Correlation (Oil vs. CPI): **r = 0.82**

---

## 📍 Conclusion

**Summary:**

* **Food inflation** remains the primary driver of India’s overall CPI due to its nearly 50% weight — making supply-side stability critical.
  
* **2022 inflation peaks** exposed vulnerabilities in supply chain resilience and dependency on global commodities, especially fuel and food.
  
* **Month-on-month volatility** in essentials directly impacts lower-income households, emphasizing the need for:
  * Food inflation 
  * 2022 inflation peaks 
  * Month-on-month 
  * Real-time agricultural price monitoring
  * Timely policy interventions (MSP, stock release)
  * Strengthened logistics and distribution systems

* Inflation management requires **real-time price monitoring** and **timely interventions**. Forward-looking preparedness — governments must anticipate lagged inflation spikes post-crisis and ensure stability in core consumer categories (food, healthcare, housing).


* Oil price fluctuations have a cascading impact across sectors; hence, **Fuel policies and tax structures (subsidies, tax control/calibration)**, **global oil market monitoring** crucial for macroeconomic stability.  

* For businesses and investors, tracking **CPI-linked sector analysis (FMCG, logistics, energy)** can guide smarter pricing and risk management decisions,
aids in hedging and informed portfolio planning.   

---

## 🖥️ Dashboard Overview

![image alt](https://github.com/Cnik1710/CPI-Consumer-Price-Index-Data-Analysis/blob/3b62c85574080b1ae24ada8a1ea20b0ce43d1dae/Inflation%20Pulse%20India%20CPI%20Tracker%20National%20Macroeconomy%20Analysis%20Final%20Report.png)

---

## ✅ Business Impact & Use Cases

* **Government & Policy Bodies:**
    Enable data-driven inflation control, subsidy allocation, and stabilization measures.

* **Economic Planners & Analysts:**
    Forecast inflation trends, assess sectoral pressures, and frame monetary responses.

* **Investors & Financial Institutions:**
    Leverage CPI–oil correlations to anticipate market movements and optimize strategies.

* **General Public & Businesses:**
    Track cost-of-living trends and adjust budgets or pricing models accordingly.

---

## 🙏 Acknowledgements

**Project Analyst:** Anik Chakraborty
📧 *[anikc1710@gmail.com](mailto:anikc1710@gmail.com)*

**Special Thanks To:**

* National Statistical Office (NSO) – for CPI data
* Petroleum Planning & Analysis Cell (PPAC) – for crude oil price data
* Coding Ninjas – for project framework and guidance

---

