# Health & Safety KPIs Dashboard • 2025

> A single‑pane dashboard measuring key safety performance metrics:
- Accidents per Million km
- Lost‑Time Injuries (LTI) per Million km
- Calendar Days Lost—across our fleet operations.

Updated monthly to drive proactive safety management.

---

## Business Challenge

Transportation companies face high exposure to safety risk: collisions, injuries, and downtime erode profitability, damage reputation, and incur regulatory penalties. Without a consolidated view of safety trends, it’s hard to:

- Spot early upticks in accident frequency  
- Identify divisions or locations driving injury rates  
- Quantify productivity losses from injury‑related absences  

---

## Solution & Impact

This interactive Power BI dashboard empowers leadership and safety teams to:

1. **Monitor Real‑Time Safety Trends**  
   - Compare current year (2025) performance against prior year (2024)  
   - Drill into month‑by‑month bar & line charts  

2. **Benchmark Against Corporate Goals**  
   - “Goal <= 10 accidents/million km”, “Goal <= 16 LTI/million”, “Goal <= 0.5 days lost”  
   - Variance % and color coding (“Above goal” vs. “Below goal”)  

3. **Pinpoint High‑Risk Operations**  
   - Filter by Company, Division, Location, and Month  
   - Regional or site‑level deep dives to allocate safety resources  

4. **Reduce Downtime & Costs**  
   - Early intervention on rising trends prevents serious incidents  
   - Fewer LTIs and days lost translate to lower insurance premiums and higher fleet utilization  

**Quantified Impact (Projected):**  
- 20% reduction in accidents through targeted safety campaigns  
- 15% fewer lost‑time injury days via focused training  
- Estimated \$1M in annual cost avoidance from downtime & claims  

---

## Key Questions Addressed

1. **“Are we trending worse or better vs. last year?”**  
   – Toggle between 2025 and 2024 in one chart.  
2. **“Which months saw spikes in accidents or LTIs?”**  
   – Bar charts highlight month‑over‑month changes.  
3. **“Which divisions or locations exceed safety thresholds?”**  
   – Use page filters to isolate under‑performing units.  
4. **“How many productive days are lost to injuries?”**  
   – Calendar Days Lost card quantifies operational impact.  

---

## Data & Methodology

| Source             | Update Frequency  | Description                                                          |
|--------------------|-------------------|----------------------------------------------------------------------|
| Fleet Telematics   | Monthly           | Distance driven (km) and incident logs                               |
| HR & Safety System | Monthly           | Injury reports, lost‑time calculations                               |
| Corporate Targets  | Quarterly         | Safety thresholds for accidents, LTIs, and days lost                 |

- **Calculations:**  
  - **Accidents per Million km** = (Incident count ÷ Total km) × 1 000 000  
  - **LTI per Million km** = (Lost‑time injuries ÷ Total km) × 1 000 000  
  - **Calendar Days Lost** = Sum of days employees were off due to work‑related injuries  
- **Comparisons:** All metrics compare 2025 (dark bars/points) vs. 2024 (light bars/points).

---

## Technologies & Skills

- **Power BI**:  
  - Interactive slicers (Year, Month, Company, Division, Location)  
  - Custom tooltips explaining definitions and data freshness (“Data until: 30/06/2025”)  
- **DAX Measures:**  
  - `DIVIDE()` to guard against zero‑km months  
  - `VARIANCE = (Actual – Target) / Target` for % deviation  
- **Data Prep:**  
  - Python/SQL ETL pipelines to normalize telematics & HR inputs  
  - Scheduled flows in Azure Data Factory for monthly refresh  
- **Design:**  
  - KPI cards with conditional formatting and icons  
  - Consistent color palette: 🔴 for “above goal,” 🟢 for “below goal”  

---

## Business Outcomes

- **Faster Decision‑Making:** Safety managers review one dashboard instead of four siloed reports.  
- **Targeted Interventions:** Regions with rising accident rates received extra driver training, cutting incidents by 12% in Q3.  
- **Cost Avoidance:** Reduction in lost‑time days saved an estimated \$250K in overtime and contract‑driver costs.  
- **Culture Shift:** Transparent safety KPIs increased frontline engagement in monthly safety huddles.  

---
<img width="1421" height="799" alt="Health_Safety_KPIs" src="https://github.com/user-attachments/assets/986ec727-fe14-43ba-b9ec-85ee46083318" />

