# Regional Patterns of Severe Weather Power Outages in the United States

Exploratory data analysis of severe weather–related power outages across the United States using the EAGLE-I Event-correlated Outage Dataset in 2023.

---

## Research Questions

- Which states experience the highest frequency of severe weather outages?
- Which states experience the most severe outages?
- How is outage impact distributed within high-impact states?

---
## Results
- Outage severity does not scale with event frequency.
- County-level concentration varies substantially across states.
---

## Highlights

- Analyzed approximately 77K outage events across the United States.
- Focused on severe weather events (>60% of all recorded outages).
- Compared outage frequency and severity at both the state and county levels.
- Identified counties contributing disproportionately to outage impacts in high-impact states.

---

## Repository

```text
US_Power_Outage_Regional_Analysis/
│
├── power_outage_regional_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## Dataset

**Event-correlated Outage Dataset in America (2023)**  
Pacific Northwest National Laboratory (PNNL)

Data sources include:

- EAGLE-I Power Outage Data
- DOE-417 Electric Emergency Incident Reports
- U.S. County Population Estimates

Dataset: https://data.openei.org/submissions/6458

---

## Limitations

- The analysis is descriptive and does not establish causality between weather conditions and outage severity.
- Outage severity is measured using customer impact only, which does not capture duration or economic losses.
