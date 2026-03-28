# 🍷 Victorian Liquor Licences — Data Analysis Case Study

A comprehensive data analysis of **23,341 active liquor licences** across Victoria, Australia, as of 31 October 2025.

---

## 📋 Project Overview

This project analyses the full Victorian liquor licence dataset published by the **Victorian Commission for Gambling and Liquor Regulation (VCGLR)** to uncover geographic, operational and category-level insights across the state.

**Tools used:** Python (pandas, matplotlib, openpyxl) · Power BI · Microsoft PowerPoint · Excel

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `VIC_Liquor_Licences_Dashboard.pdf` | Full 11-slide analysis dashboard (charts, KPIs, insights) |
| `VIC_Liquor_Licences_CLEANED.xlsx` | Cleaned dataset ready for Power BI or further analysis |

---

## 🔍 Key Findings

- **63%** of all licences are in Metro Victoria — Melbourne City Council alone holds 2,155
- **Restaurant & Café** is the #1 licence type at 28% of total (6,544 licences)
- **85%** of late-night licences (trading 3am+) are in Metro areas, concentrated in Metro North
- Only **2.1%** of venues (480) hold gaming licences — tightly concentrated in pubs and clubs
- **Hume & Loddon Mallee** regions lead producer licences, covering King Valley, Heathcote and Rutherglen wine regions
- **Casey, Wyndham & Moreland** rank highest for packaged liquor licences, reflecting Melbourne's outer suburban growth corridors

---

## 🗂️ Dataset

- **Source:** [liquor.vic.gov.au](https://www.liquor.vic.gov.au)
- **Records:** 23,341 active licences
- **Date:** 31 October 2025
- **Columns:** Licence Number, Licensee, Trading As, Category, Trading Hours, Maximum Capacity, Suburb, Postcode, Latitude, Longitude, Council, Region, Metro/Regional, Gaming

### Data Cleaning Applied
- Removed 1,276 rows with null or `[Not applicable]` Suburb values (predominantly Pre-retail warehouse licences)
- Replaced junk text values (`"NOT APPLICABLE"`) in Council and Address fields with blank cells
- Filled 198 null `Trading As` values with the corresponding Licensee name

---

## 📊 Dashboard Preview

The PDF dashboard covers:

1. Cover slide
2. Executive Summary — 8 KPI cards
3. Licence Categories breakdown
4. Metro vs Regional analysis
5. Geographic hotspots (councils & suburbs)
6. Late Night Trading & Gaming
7. Trading Hours breakdown
8. Producer's Licences & Retail Network
9. Venue Capacity Analysis
10. Key Insights & Findings
11. Closing summary

---

## 👤 Author

**Steven Chhay**
Data Analyst · Melbourne, VIC
[GitHub](https://github.com/chhay0818)
