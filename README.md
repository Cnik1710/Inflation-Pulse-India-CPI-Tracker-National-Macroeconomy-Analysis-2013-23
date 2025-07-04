---

# India CPI Inflation Case Study 📈

---

## 📄 Project Overview

This case study analyzes India's Consumer Price Index (CPI) data to uncover inflation trends, assess category-wise contributions, and evaluate external macroeconomic impacts like COVID-19 and global oil prices. The study is structured to help analysts, policymakers, and economic strategists understand inflation drivers and patterns across time and sectors.

---

## 🎯 Purpose

To deliver a structured, visual, and data-driven analysis of India's CPI data. This helps:

* Identify key inflation contributors
* Analyze historical and recent inflation trends
* Understand the impact of global and domestic events on Indian inflation

---

## 🧰 Tech Stack

The project was developed using:

* 🟨 **Microsoft Excel** – Primary tool for data transformation, analysis, and visualization
* 📉 **Graphs & Charts** – Line graphs, bar charts, correlation matrices
* 📊 **Functions** – Logical, statistical, and lookup formulas including `=CORREL`, `=IF`, `=AVERAGE`, `=PERCENTCHANGE`
* 🧮 **Data Imputation** – Used moving averages and linear interpolation for missing values

---

## 🗃️ Dataset Details

**Source:** National Statistical Office (NSO), Government of India

* Data includes monthly CPI values for Rural (CPI-R), Urban (CPI-U), and General (combined) indexes
* Covers various CPI categories: Food, Fuel & Light, Clothing, Housing, Medical, Transport, etc.
* CPI is an index, not direct price levels—used to compute relative price changes
* Data spans multiple years: 2017 to 2023
* Missing values imputed using 3-month moving average technique

---

## 🔍 Key Features / Case Components

### 1️⃣ **Category Contribution to CPI**

* Subcategories aggregated into broader buckets: Food, Energy, Transportation, Healthcare, etc.
* Relative weight assigned equally across categories for simplified modeling
* **Key Insight:** Food category shows the highest contribution to CPI across months

---

### 2️⃣ **Year-on-Year CPI Growth Since 2017**

* Y-o-Y CPI (Urban + Rural combined) computed for each year
* **Visualization:** Line chart highlighting annual inflation trends
* **Highest Inflation Year:** \[Year] with key factors like global supply disruptions or policy changes

---

### 3️⃣ **Retail Inflation Trends: Nov 2022 – May 2023**

* Focused analysis on monthly food inflation
* Identified months with **peak** (e.g., Nov '22) and **lowest** inflation
* **Top Subcategory Impact:** Pulses & Vegetables caused largest price volatility

---

### 4️⃣ **COVID-19 Impact on CPI**

* Compared pre-COVID (before Mar 2020) vs. post-COVID inflation
* Categories like **Healthcare, Food, and Essential Services** showed inflation spikes
* **Reason:** Panic buying, disrupted supply chains, and demand shifts during lockdown

---

### 5️⃣ **Global Oil Price Influence (2021–2023)**

* Imported crude oil prices correlated with CPI changes
* Used correlation analysis to identify sensitive CPI categories
* **Top Correlated Category:** Transportation & Fuel
* Formula used: `=CORREL(oil_price_series, cpi_category_series)`

---

## 📈 Key Visuals Included

* Yearly CPI Inflation Line Graph
* MoM Food Inflation Trend Bar Chart
* Category-wise CPI Contribution Pie Chart
* Pre vs. Post COVID CPI Comparison Bar Graph
* Correlation Heatmap for Oil Prices vs. CPI Categories

---

## 💡 Business Impact & Insights

* **Policy Use:** Helps identify inflation hotspots for government intervention
* **Economic Planning:** Enables better forecasting and budget allocation
* **Investment Strategy:** Correlation with global oil price can guide commodity-based investments
* **Public Awareness:** Educates citizens on key inflation drivers affecting their cost of living

---

## 📌 Data Methodology & Calculations

* **Monthly Inflation:**

  $$
  \text{Monthly Inflation Rate} = \left( \frac{\text{CPI}_{\text{current}} - \text{CPI}_{\text{previous}}}{\text{CPI}_{\text{previous}}} \right) \times 100
  $$
* **Annual Inflation:**

  $$
  \text{Annual Inflation Rate} = \left( \frac{\text{CPI}_{\text{end}} - \text{CPI}_{\text{start}}}{\text{CPI}_{\text{start}}} \right) \times 100
  $$
* **Correlation Coefficient (Excel):**
  `=CORREL(range1, range2)` to assess external price shocks (e.g., oil)

---

## 🙏 Acknowledgements

* **National Statistical Office (NSO), Government of India** – Data Source
* **Petroleum Planning & Analysis Cell (PPAC)** – Oil Price Dataset
* **Coding Ninjas** – Project Framework and Learning Support

---

## 👨‍💻 Contributor

**Analyst:** Anik Chakraborty
📧 Email: [anikc1710@gmail.com](mailto:anikc1710@gmail.com)

---
