# DAY_99_Space_Exploreation_till_2020_UDEMY

# Space Mission Analysis (1957 – Present)

An exploratory data analysis (EDA) of space mission launches from the start of the Space Race in 1957 to 2020. This repository analyzes launch frequencies, organization contributions, mission success rates, and costs.

## 📊 Dataset Overview

The dataset contains scraped data from [nextspaceflight.com](https://nextspaceflight.com/launches/past/?page=1) with **4,324 launch records**.

### Features:
- **Organisation**: Launch company/agency (e.g., NASA, SpaceX, RVSN USSR)
- **Location**: Launch pad and country location
- **Date**: Date and time of launch (UTC)
- **Detail**: Rocket model and mission payload details
- **Rocket_Status**: Status of the rocket (`StatusActive` or `StatusRetired`)
- **Price**: Mission cost in millions of USD (where available)
- **Mission_Status**: Outcome (`Success`, `Failure`, `Partial Failure`, etc.)

---

## 🛠️ Requirements & Installation

Install the required Python packages before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn plotly iso3166 country_converter
```
