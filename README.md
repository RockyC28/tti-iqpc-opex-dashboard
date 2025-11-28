# Automated Production Dashboards for IQPC and OPEX

## 1. Project Overview
In this project, I built automated data pipelines and interactive dashboards to track production and quality performance for the IQPC (In-Quality Process Control) and OPEX (Operational Excellence) programs at Techtronic Industries (TTI).  
The goal was to replace manual Excel-based reporting with a consistent, near real-time view of line performance that managers and engineers could use every day.

**Key outcomes:**
- Reduced manual reporting work by automating daily data refresh and calculations.
- Enabled production and quality managers to monitor key metrics by line, product, and shift in one place.
- Improved visibility into defect trends and bottlenecks, supporting faster root-cause analysis and decision-making.

---

## 2. My Role and Skills Demonstrated
I worked as a **Data Analyst Intern** on the Business Systems Team and was mainly responsible for:

- **Data work**: Extracted and merged data from SQL Server and Excel logs; standardized product, line, and time fields.
- **Modeling / analysis**: Defined and calculated metrics such as defect rate, rework rate, output by line, and First Pass Yield.
- **Visualization / product**: Designed and built Power BI dashboards for IQPC and OPEX with drill-down filters and clear KPI views.
- **Collaboration**: Communicated with engineers, QA staff, and managers to understand their needs and iterate on dashboard layouts.

This project highlights my skills in:
- Python (pandas) for data cleaning and transformation
- SQL for querying, joining, and aggregating production and quality data
- Power BI for data modeling, DAX measures, and interactive dashboards
- Cross-functional communication and documentation of metrics and workflows

---

## 3. Data and Methods
**Data sources:**
- Production line logs from SQL Server (output, cycle time, downtime)
- Quality inspection records from internal systems (defects, rework, scrap)
- Reference tables for products, lines, shifts, and dates

**Main steps:**
1. **Data extraction**  
   - Wrote SQL queries to pull daily production and defect data from multiple tables and exports.
2. **Cleaning & transformation**  
   - Handled missing values, removed duplicates, and aligned timestamps; created shift, day, and product-level aggregates.
3. **Analysis / metrics**  
   - Calculated defect rates, rework rates, throughput, and other IQPC/OPEX KPIs at different levels (line, product, shift, day).
4. **Dashboard / product**  
   - Built interactive Power BI pages that allow users to filter by date range, line, product family, and defect type, with KPI cards, trend charts, and detailed tables.

---

## 4. Results and Impact
Some key results from the project:

- Managers can now track defect hotspots by product, line, and time of day without manually combining spreadsheets.
- The dashboards help identify lines or stations with abnormal trends, supporting targeted root-cause analysis.
- Weekly and monthly reports can be generated directly from the dashboards, greatly reducing the time spent on manual reporting.

These results show how data engineering and visualization can directly support factory operations, quality improvement, and decision-making.

---

## 5. How This Connects to My Career
This project is important for my career because it shows that I can:

- Take messy, real-world factory data and turn it into a usable analytics product.
- Communicate technical results in a way that non-technical stakeholders can understand and act on.
- Work across business and technical teams to define metrics and build tools that people actually use.

I want to continue developing as a **Business/Data Analyst** working on projects that connect data with real business problems, especially in operations, supply chain, and process improvement.
