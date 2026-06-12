# Food Claims Process Analysis — Vivendo

![close-up-delicious-fast-food-meal (1)](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/f9acff85-3368-41a7-911a-1f230185a944)

Operational efficiency analysis for Vivendo, a major fast-food chain in Brazil, examining how quickly four regional legal offices resolve food poisoning claims — and identifying where process improvements would have the greatest impact.

**Business question:** Which locations are slowest to close claims, and what does the data suggest about why?

---

## Key findings

| Location | Median closure time | Variability (IQR) |
|---|---|---|
| **FORTALEZA** | Shortest | Lowest — most consistent |
| **NATAL** | Second shortest | Low |
| **RECIFE** | Above average | Moderate — highest claim volume |
| **SAO LUIS** | Longest | Highest — most variable |

RECIFE handles the highest volume of claims but is not the slowest to close them — suggesting a capacity issue rather than a process issue. SAO LUIS has both the longest median closure time and the widest spread, indicating systemic inefficiency.

---

## Visualisations

**Claims by location**
![visualization](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/d4de4357-e01c-4126-8462-c1a374ca948f)

**Time to close — distribution**
![Task 3](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/3144c61e-71a5-472c-85b9-bb9460e5db2b)

**Time to close by location — box plot**
![Box Plot Task 4](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/66c43ab1-797f-4d5f-a3f1-3e3219e54191)

---

## Tools used

- **Excel** — data cleaning, EDA, visualisation
- **Data source** — `food_claims_2212_a.csv` (included in repo)

---

## Process

**Data cleaning**
- Loaded and inspected claims dataset
- Handled missing values across claim status and closure date fields
- Standardised location name formatting

**Analysis**
- Counted claims per location to understand volume distribution
- Plotted time-to-close histogram to identify distribution shape and outlier clusters
- Built location-level box plots to compare median, IQR, and outliers across all four offices

---

## Recommendations

1. **Prioritise SAO LUIS** — highest median closure time and most variability; review end-to-end claims process for unnecessary steps or bottlenecks
2. **Resource rebalancing for RECIFE** — high volume with moderate closure times suggests the team is stretched; additional capacity would reduce queue build-up
3. **Benchmark FORTALEZA practices** — shortest and most consistent closure times; document their process and use it as the standard for other locations
4. **Ongoing monitoring** — track median closure time monthly per location; set a target of ≤ FORTALEZA median for all offices within 2 quarters

---

## Files

| File | Description |
|---|---|
| `README.md` | This file |
| [Download here](https://docs.google.com/spreadsheets/d/1n_zkpd_ejAqG5APHvrkp8wVMdNnjwqY-DKZMPyfcVQs/edit?usp=sharing)| Raw dataset |
| `screenshots/` | Visualisation screenshots |







