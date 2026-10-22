# Housing Society Billing & Collections Analysis

**Full-year analysis (Apr 2025 – Mar 2026)** of billing and collections across 8 housing societies in the Mumbai Metropolitan Region.
 
![Dashboard Preview](assets/dashboard-preview.png)  
*Interactive Excel Dashboard – KPI cards, monthly trends, area/society breakdowns & charts*

---

## 📊 Project Overview

This repository contains a complete **Billing & Collections Analysis** for eight residential societies located in:

- Powai  
- Mulund  
- Bhiwandi  
- Kalyan  
- Andheri  
- Thane  
- Navi Mumbai  
- Dombivli  

**Dataset**: 10,000 invoice-level records covering Maintenance, Water, Parking, Late Fees and Other charges.

### Key Headline Metrics

| Metric                  | Value          |
|-------------------------|----------------|
| **Total Billed**        | ₹3.82 Crore    |
| **Total Collected**     | ₹3.06 Crore    |
| **Total Outstanding**   | ₹0.76 Crore    |
| **Overall Collection Rate** | **80.2%**  |
| Paid Invoices           | 7,489 (74.9%)  |
| Partially Paid          | 1,016 (10.2%)  |
| Unpaid                  | 1,495 (15.0%)  |

---

## 📁 Repository Contents



---

## 🖥️ Interactive Excel Dashboard

The accompanying Excel workbook (`Housing_Society_Billing_Dashboard.xlsx`) contains **four sheets**:

| Sheet              | Description |
|--------------------|-------------|
| **Dashboard**      | KPI cards, monthly trend tables, area/society/flat-type summaries + **6 interactive charts** |
| **Cleaned Data**   | Full 10,000-row transactional dataset (AutoFilter + frozen header) |
| **Pivot Summaries**| Pre-calculated monthly, area, society & payment-status tables |
| **Raw Data**       | Backup copy of cleaned data for audit |

### Charts Included
1. Monthly Billed vs Collected (Line)
2. Payment Status Distribution (Pie)
3. Outstanding by Area (Column)
4. Outstanding by Society (Horizontal Bar)
5. Monthly Collection Rate (Line)
6. Invoices by Flat Type (Pie)

### How to Use the Dashboard
1. Open `Housing_Society_Billing_Dashboard.xlsx`
2. Go to the **Dashboard** sheet for high-level KPIs and visuals
3. Use **AutoFilter** on the Cleaned Data sheet (Society, Area, Billing Month, Payment Status, Flat Type, Occupancy)
4. For true interactive Slicers: Create a PivotTable from Cleaned Data → Insert → Slicer

---

## 🔍 Key Insights

### Collection Health
- Healthy overall collection rate of **80.2%**
- Unpaid invoices account for **₹57.8 lakh** (~76% of total outstanding)
- Partially paid invoices contribute another **₹17.8 lakh**

### Priority Areas for Recovery
Highest outstanding balances:
1. **Mulund** – ₹10.4 lakh
2. **Navi Mumbai** – ₹9.7 lakh
3. **Powai** – ₹9.5 lakh

### Recommended Recovery Sequence
1. **Immediate** – Contact all Unpaid invoices older than 60–90 days (especially high-value 3/4 BHK)
2. **Short-term** – Follow up Partially Paid accounts
3. **Process** – Enable online payment reminders + consistent late-fee enforcement
4. **Analytics** – Monthly dashboard refresh with target of 85–88% collection rate

---

## 📈 Data Coverage

| Dimension          | Details |
|--------------------|---------|
| Societies          | Lakeview, Sunrise, Green Heights, Royal Orchid, Maple, Palm Gardens, Harmony, Silver Oak |
| Flat Types         | 1 BHK (~20%), 2 BHK (~48%), 3 BHK (~27%), 4 BHK (~5%) |
| Occupancy          | Owners 62% \| Tenants 38% |
| Billing Period     | Apr 2025 – Mar 2026 (monthly) |
| Geographic Areas   | 8 locations across MMR |

---

## 🛠️ How to Reproduce / Extend

1. Clone this repository
2. Open the Excel dashboard and explore with filters
3. Use the cleaned CSV for further analysis in Python / Power BI / Tableau
4. Re-run the analysis after each billing cycle to track improvement

---

## 📌 Next Steps for Facility Management Team

- Export Unpaid + Partially Paid lists and assign to collection officers by society
- Set a monthly dashboard review cadence
- Evaluate digital payment incentives / automated reminders
- Track collection-rate trend by society and aim for 85%+

---

## 📄 Full Report

See the detailed analysis in:  
**[Housing_Society_Billing_Collections_Report.docx](Housing_Society_Billing_Collections_Report.docx)**

---

**Created for Facility Management performance tracking & recovery prioritization**  
*Data Period: April 2025 – March 2026*
