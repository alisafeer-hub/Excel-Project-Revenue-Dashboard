# Excel Revenue Dashboard 📊

> An interactive Excel dashboard for analyzing global sales revenue across regions, product categories, markets, and time periods — with dynamic slicers for fully customizable views.

📂 Dashboard file: `Excel-Revenue-Dashboard.xlsx`

---

# INTRODUCTION

This project is an interactive sales revenue dashboard built entirely in Microsoft Excel. The dashboard is designed to give business stakeholders a flexible, at-a-glance view of sales performance — sliced and filtered any way they need.

Rather than static charts, the entire dashboard is driven by **dynamic slicers**, allowing users to explore the data from multiple angles:

- 🌍 **By Region** — Europe, North America, Pacific
- 📅 **By Year** — 2002, 2003, 2004
- 🎨 **By Color** — Black, Blue, Multi, Red, Silver, Silver/Black, White, Yellow
- 📦 **By Category** — Bikes, Accessories, Clothing, Components

Every chart and KPI on the dashboard updates instantly when a slicer selection is changed, making it a powerful self-service analytics tool.

---

# BACKGROUND

This dashboard was built to practice and demonstrate core Excel data analytics skills — transforming raw transactional sales data into a clean, interactive reporting tool.

The dataset contains detailed sales records including:

- Region, Sub-Region, and Market
- Customer and Business Segment
- Product Category, Model, and Color
- Sales Date, List Price, Unit Price, Order Quantity, and Sales Amount

The goal was to build a dashboard that answers key business questions without needing a separate BI tool — entirely within Excel.

---

# TOOLS I USED

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Core platform for data analysis, visualization, and dashboard building |
| **Pivot Tables** | Summarizing and aggregating raw sales data by multiple dimensions |
| **Pivot Charts** | Visualizing trends, breakdowns, and comparisons dynamically |
| **Slicers** | Enabling interactive, one-click filtering across all dashboard visuals |
| **Excel Formulas** | Supporting calculations for KPIs and summary metrics |

---

# THE ANALYSIS

The dashboard answers several key business questions through its visual components:

### 1. 🥧 Revenue Share by Region
A donut/pie chart breaks down total revenue contribution by region:
- **North America** dominates at **84%** of total revenue
- **Europe** contributes **14%**
- **Pacific** accounts for **2%**

This gives immediate visibility into which region drives the business and where growth opportunities may exist.

---

### 2. 📈 Monthly Revenue Trends by Category (2002–2004)
A multi-line trend chart tracks monthly revenue across all four product categories — Accessories, Bikes, Clothing, and Components — over the full three-year period.

**Finding:** Bikes consistently generate the highest revenue, with notable seasonal peaks. Accessories and Clothing show relatively stable, low-volume patterns throughout.

---

### 3. 📊 Year-over-Year Revenue by Category (Bar Chart)
A horizontal bar chart compares annual revenue by category across 2002, 2003, and 2004.

**Finding:** Revenue from Bikes grew year-over-year, while Components and Clothing remained relatively flat — indicating the core product line is expanding while accessories lag behind.

---

### 4. 🗺️ Revenue by Market and Sub-Region
A clustered bar chart visualizes revenue performance across individual markets within each region — including France, Germany, United Kingdom, Canada, Central, Northeast, Northwest, Southeast, Southwest (North America), and Australia (Pacific).

**Finding:** The Southwest and Northwest US markets are the strongest performers within North America, while Australia represents an early-stage opportunity in the Pacific region.

---

### 5. 🎛️ Dynamic Slicer Filtering
All visuals are connected to four slicers — Region, Year, Color, and Business Segment — allowing any combination of filters to be applied simultaneously. This makes the dashboard fully reusable for any ad-hoc analysis without touching the underlying data.

---

# WHAT I LEARNED

- **🔗 Connecting Slicers to Multiple Pivot Tables** — Learned how to link a single slicer to multiple pivot charts simultaneously so all visuals update in sync with one click.

- **📐 Dashboard Layout & Design** — Practiced structuring a clean, professional dashboard layout that balances information density with readability.

- **📊 Choosing the Right Chart Type** — Applied judgment on when to use pie/donut charts (part-to-whole), line charts (trends over time), and bar charts (comparisons across categories).

- **🧹 Data Preparation** — Worked with raw transactional data containing regions, sub-regions, customers, products, colors, and dates — structuring it into pivot-ready format.

- **⚡ Excel as a BI Tool** — Demonstrated that Excel, when used well, can deliver powerful interactive dashboards without needing Power BI or Tableau.

---

# CONCLUSIONS

This dashboard surfaces several actionable insights from the sales data:

1. **North America is the Core Market** — At 84% of total revenue, North America is by far the most important region. Europe at 14% is a meaningful secondary market worth investment.

2. **Bikes Drive Revenue** — Bikes are the dominant product category by a wide margin. Any business strategy should prioritize protecting and growing this segment.

3. **Seasonality Exists** — Monthly trend data reveals revenue peaks and dips throughout the year, which is useful for inventory planning and promotional timing.

4. **Pacific Region is Underdeveloped** — At just 2% of revenue, the Pacific (primarily Australia) represents a long-term growth opportunity.

5. **Color & Segment Filters Enable Deeper Insights** — The ability to slice by product color and business segment opens up customer preference analysis that is not visible at the category level alone.

**The bottom line:** A well-built Excel dashboard can deliver board-level insights from raw transactional data — no specialized software required.

---

*Dataset: Dashboard built using Microsoft Excel with Pivot Tables, Pivot Charts, and Slicers.*
