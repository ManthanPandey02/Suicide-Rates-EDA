# 🌍 Suicide Rates Analysis (1990–2022)

> **Content note:** This repository contains analysis of suicide data and may be distressing to some readers.  
> If you are in crisis or thinking about self-harm, please contact your local emergency number or a trusted crisis support line in your country.

---

## 📌 Project Overview

This repository contains a data-driven analysis of global suicide trends from **1990 to 2022**, with a focus on:

- How suicide **counts and rates** have changed over time  
- Differences across **sex**, **age groups**, and **generational cohorts**  
- The contribution of **high-population countries** to the global suicide burden  
- The relationship between suicide rates and **socioeconomic indicators** such as GDP, inflation, and employment ratios  

The goal of this project is to provide **evidence-based insights** that can support policymakers, public health organizations, and mental health advocates in designing **targeted suicide prevention strategies**.

---

## 🧪 Research Questions

1. How have global suicide **counts** and **rates per 100,000** evolved between 1990 and 2022?
2. Are there systematic differences in suicide rates by **sex**, **age group**, and **generation**?
3. How do **population size quantiles (Q1–Q4)** relate to absolute and relative suicide burden?
4. Which **countries** contribute most to the global suicide burden within the largest population quantile?
5. How strongly are suicide rates associated with **macroeconomic variables** like GDP, GDP per capita, GNI, inflation, and employment ratio?

---

## 🧾 Data

### Main Dataset

- `data/suicide_rates_1990-2022.csv`  
  Contains annual, country-level records with:

- `CountryName`
- `Year`
- `Sex`
- `AgeGroup`
- `Generation`
- `Population`
- `SuicideCount`
- `DeathRatePer100K`
- `GDP`
- `GDPPerCapita`
- `GrossNationalIncome`
- `GNIPerCapita`
- `InflationRate`
- `EmploymentPopulationRatio`

> **Note:** In the original notebook, an age-standardized dataset was also referenced.  
> If used, it should be stored as `data/age_std_suicide_rates_1990-2022.csv` and loaded into a separate dataframe (e.g., `df_age_std`) rather than overwriting the main dataset.
