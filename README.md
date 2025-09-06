# US Accidents Analysis (2016-2023)

An exploratory analysis of the **US-Accidents** dataset (Feb-2016 → Mar-2023) covering ~7.7 M traffic incidents across 49 states.  
The goal is to understand **when, where, and under what conditions** accidents most often occur, and to highlight factors that may guide safety improvements.

---

## Dataset

- **Source:** [US Accidents (2016-2023) – Countrywide Traffic Accident Dataset](https://www.kaggle.com/sobhanmoosavi/us-accidents)
- **Records:** ~7.7 million
- **States Covered:** 49 (all but Hawaii)
- **Collection Method:** Streaming traffic APIs from state DOTs, law enforcement, traffic cameras, and sensors.
- **License:** CC BY-NC-SA 4.0 (research & academic use only)

---ِ

## Key Findings

### 1. Time Analysis
- **Severity:** Majority are **Severity 2** accidents.
- **Rush Hour Peaks:** **7–9 AM** and **4–5 PM** on weekdays (commuting times).
- **Yearly Trend:** Accidents **rise in August**, **peak in December**, **decline from January** (holiday travel + winter effects).
- **Day of Week:** Highest on **Fridays & Thursdays**, lowest on **Saturdays & Sundays**.

### 2. Location Analysis
- **Top States by Count:** California (CA), Florida (FL), Texas (TX).
- **Higher-Severity States:** Rhode Island (RI), Kentucky (KY) → Severity 3; South Dakota (SD) → Severity 4.
- **High-Count Cities:** Miami, Los Angeles, Houston.
- **County with Most Severity-4:** Los Angeles.
- **Typical Duration:** ~48–49 minutes.

### 3. Weather & Environmental Factors
- **Temperature:** Most crashes occur in **mild** weather, not extreme heat/cold.
- **Wind:** Mostly under **calm/light** conditions; direction widely distributed.
- **Pressure:** Normal pressure; little direct influence.
- **Humidity:** Accidents increase when **humidity > 70%** (rain/fog).
- **Visibility:** Around 80% of crashes happen in **daylight with good visibility**, though winter **fog** can still pose significant risk.

### 4. Road & Infrastructure
- **Traffic Signals:**  
  - Roads **without signals** show the **longest average accident distance** (>60 mi).  
  - **Signalized roads** average ~21–23 mi.
- **Crossings:** ~85% of accidents at locations **without signals**, ~89% **away from crossings**.
- **High-Risk Roads:** Interstates **I-95, I-5, I-10** dominate the top-20 accident streets.
- **Clustering:** Most crashes occur close to **major intersections** and within **urban centers**, where traffic density is highest.

---

## Insights & Implications

- **Targeted Safety Measures:** Focus on **rush-hour** and **high-density corridors**.
- **Traffic Control:** Improve **signalization & crossings** in rural or semi-urban roads.
- **Weather Awareness:** Most accidents occur under **good visibility**, but risks increase during **foggy or high-humidity winter conditions**, so timely driver alerts are important.
- **Urban Planning:** Accident “hotspots” (Los Angeles County, Miami, Houston) can benefit from **infrastructure audits**.

---

## Inspiration & Next Steps

The dataset supports:
- Accident **hotspot mapping**
- **Predictive modeling** (real-time risk alerts)
- Studying **weather impacts** on crash likelihood
- Evaluating **COVID-19** impacts on traffic trends

---

## Usage

This repository contains:
- Data exploration notebooks
- Visualizations of time, location, and weather patterns
- Key metrics and reproducible scripts for further research


---

[NoteBook on Kaggle](https://www.kaggle.com/code/kirellosyoussefsamy/usaccidents)

[Youtube link](https://youtu.be/vfC9AQtMvs8)

## Collaborators
- [Ali Ahmed Ali](https://github.com/Ali-AhmedAli)
- [Tasneem Samir Mohamed Beddah](https://github.com/username2)
- [Nour-Soliman](https://github.com/Nour-Soliman)
