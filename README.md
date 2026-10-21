 
# 📉 Global Tech Layoffs Analysis (2020–2025)

An end-to-end data analytics project examining **752,040 tech workforce reductions** across **2,673 events**, **1,913 companies**, and **54 countries** between March 2020 and July 2025.

---

## 📌 Executive Summary

Following the post-2020 low-interest tech expansion, global macroeconomic shifts, inflation, and interest rate hikes triggered an unprecedented wave of corporate restructuring. This project analyzes the velocity, geographic distribution, sector concentration, and enterprise severity of global workforce reductions.

### Key Headlines
- **Total Headcount Impact:** 752,040 employees laid off across 2,673 discrete events.
- **Historical Peak:** **2023** was the single deadliest year (264,220 layoffs), with **Q1 2023 representing 22.28% (167,574)** of all recorded layoffs.
- **Geographic Dominance:** The **United States** accounts for **68.99% (518,812)** of global reductions.
- **Enterprise Scale:** Publicly traded companies (**Post-IPO**) account for **58.38% (439,048)** of all cuts.
- **Mass Layoff Severity:** Events cutting 1,000+ employees account for **54.64% (410,943)** of total workforce reductions.

## 📌 Key Statistical Trends & Macro Observations
1. Temporal Wave & Peak Velocity (Q1 2023 Shock)
   - 2020 (Pandemic Outbreak): Initial disruption resulted in 80,998 layoffs across 475 events (median event size: 60 employees).
   - 2021 (Low-Rate Capital Boom): Layoffs fell to an all-time low of 15,823 across 31 events.
   - 2022 (Macro Reversal & Rate Hikes): Surged $1,044\%$ YoY to 165,269 layoffs across 821 events.
   - 2023 (Historical Peak): Reached a high of 264,220 layoffs across 845 events. Q1 2023 alone accounted for 167,574 reductions (22.28% of the entire 5-year total) across 378 events.
   - 2024–2025 (Right-Sizing & AI Realignment): 2024 recorded 152,922 layoffs across 388 events. Through July 2025, 72,808 layoffs occurred across 113 events, driven by large enterprise restructurings (Intel, Microsoft).
2. Geographic Concentration (US Dominance)
   - United States: Dominates global layoffs with 518,812 workforce reductions (68.99% global share) across 1,687 events and 1,179 companies.
   - Secondary Hubs: India (59,216 / 7.87%), Germany (30,842 / 4.10%), United Kingdom (21,280 / 2.83%), and Netherlands (19,125 / 2.54%).
   - Top 5 Country Concentration: The top 5 countries account for 86.33% (649,275) of all global layoffs.
   - Geographic Concentration Share (%)

```
United States  [==================================================] 68.99%
India          [======] 7.87%
Germany        [===] 4.10%
United Kingdom [==] 2.83%
Netherlands    [==] 2.54%
Other (49 Hubs)[=====] 11.67%
```

3. Industry & Sector Disruption
   - Hardware: Generated the highest volume of reductions at 81,428 layoffs across 44 events, exhibiting the highest median event size (305.5 employees).
   - Consumer Tech & Retail: 76,468 (Consumer) and 73,721 (Retail) layoffs across 384 combined events, reflecting reduced discretionary consumer spending post-pandemic.
   - Transportation & Finance: 64,066 (Transportation) and 52,173 (Finance across 326 events).
   - Top 5 Sector Concentration: The top 5 sectors (Hardware, Other, Consumer, Retail, Transportation) aggregate to 376,174 layoffs (50.02% of total).
4. Enterprise Scale & Funding Stage Exposure
   - Post-IPO Dominance: Publicly traded companies account for 439,048 layoffs (58.38% of total) across 652 events. Large caps absorbed the bulk of post-pandemic correction.
   - Venture-Backed Exposure: Late-stage startups suffered heavily: Acquired (67.5), Series B (30.3), Series C (26.8), and Series D (26.5).
   - Corporate Concentration: The top 10 companies by headcount reduction account for 198,905 layoffs (26.45% of total):
     a. Intel: 38,115 (driven by major 2024–2025 cuts of 15 and 22
     b. Microsoft: 30,013
     c. Amazon: 27,940
     d. Meta: 24,700
     e. Tesla: 14,500
     f. Cisco: 14,300
     g. Google: 13,547
     h. Dell: 12,650
     i. Salesforce: 12,140
     j. SAP: 11,000
5. Event Severity Distribution
   - Mass Layoffs (> 1,000 employees): 142 events generated 410,943 workforce cuts (54.64% of total).
   - Mega Layoffs (> 5,000 employees): 20 events generated 192,750 cuts (25.63% of total).
   - Small-to-Mid Events (50-199 employees): Accounted for the highest frequency of events (1,171 events / 43.81%), but only 114,337 total layoffs (15.20%).
---

## 📂 Repository Structure

```text
├── data/
│   ├── Layoffs_data_events.csv        # Primary event-level fact dataset (2,673 rows)
│   ├── layoffs_yearly_summary.csv     # Yearly aggregated summary
│   ├── layoffs_country_summary.csv    # Country level summary (54 countries)
│   └── layoffs_industry_summary.csv   # Industry level summary (31 sectors)
├── sql/
│   └── layoff_analytics_queries.sql   # Production SQL queries (DDL, Quality Checks, Analytics)
├── powerbi/
│   └── Global_Layoffs_Dashboard.pbix  # Interactive 4-page Power BI Dashboard
├── docs/
│   ├── Executive_Data_Documentation.md# Comprehensive project documentation & data dictionary
│   └── KPI_Definitions_Matrix.md      # KPI formulas and business definition framework
└── README.md                          # Project overview and setup guide


```
## 📊 Dashboard
<img width="602" height="339" alt="Screenshot 2026-10-21 123440" src="https://github.com/user-attachments/assets/aa62557b-20c8-4e73-b80f-f8900f3b83fd" />

<img width="602" height="344" alt="Screenshot 2026-10-21 123505" src="https://github.com/user-attachments/assets/9ede22d4-5ce1-4b0c-a0a4-cb65767889af" />

<img width="603" height="342" alt="Screenshot 2026-10-21 123521" src="https://github.com/user-attachments/assets/1f094fc8-2dff-4967-95eb-1c611690825c" />

<img width="603" height="336" alt="Screenshot 2026-10-21 123537" src="https://github.com/user-attachments/assets/5962d274-a067-4b7f-8835-ccc2c1cf564a" />


## 📉 Recommendations
1. Transition from Reactive Mass Cuts to Continuous Elastic Rightsizing: With 54.6% (410,943) of all layoffs concentrated in mass events (1,000 employees), single-day mega-cuts inflict severe damage on employer brand, employee morale, and operational continuity. Leadership should implement quarterly headcount elasticity checks tied directly to Revenue per Employee and Operating Margin thresholds rather than waiting for macro downturns to execute double-digit percentage slashes.
2. Cross-Skill Talent in High-Volatility Sectors: Hardware (81,428 layoffs, median event size 305.5) and Consumer Tech (76,468 layoffs) exhibit extreme cyclicality. Organizations operating in these verticals should build internal mobility programs that reallocate engineering and operational staff into steady revenue lines (e.g., Enterprise B2B, AI infrastructure) during sector contractions.
3. Evaluate Sector Volatility Before Career Moves: Sectors like Hardware, Consumer Tech, Retail, and Transportation suffered the heaviest losses (376,174 combined layoffs). Tech professionals in these fields should cultivate cross-industry skills (such as cloud engineering, data management, and cybersecurity) that translate easily into lower-volatility sectors like Healthcare and Public Infrastructure.
4. Factor Geographic Labor Regulations into Career Decisions: While US tech roles offer higher compensation, European hubs like Germany (30,842 layoffs) and the UK (21,280) feature statutory severance and consultation periods that cushion the impact during corporate restructurings.

## 📉 Conclusion
The post-2020 tech contraction proves that hyper-expansion tied solely to headcount is fundamentally unsustainable. Moving forward, organizational resilience hinges on shifting from reactive mass downsizing to continuous workforce planning, prioritizing revenue per employee, disciplined cash burn, and proactive talent mobility across core sectors.
