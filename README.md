# 🦠 Epidemic Simulator with Multiple Hospitals, Variants, and Economic Impact

A detailed agent-based epidemic simulation built using Python and Pygame. This project models disease spread, multiple virus variants, age-based vulnerability, vaccination campaigns, dynamic hospital capacity, and economic productivity over time.

---

## 🚀 Features

- 👤 Agent-based simulation on a 2D grid (50x50 people)  
- 🧬 Multiple virus variants with unique infection, mortality, and vaccine resistance profiles  
- 💉 Phased vaccination rollout by age group  
- 🏥 Multiple hospitals with capacity, admission, discharge, and impact on survival  
- 🧓 Age-based vulnerability and color-coded visuals (children, adults, elders)  
- 📈 Lockdown triggers based on infection rate (reduces spread)  
- 💸 Economic productivity modeling based on healthy population  
- 👶 Birth simulation of immune (recovered) children  
- 🎨 Pygame visualization with borders for infection variants and hospitalizations  
- 📊 Matplotlib graphs of infection trends and economic impact  

---

## 🛠️ Requirements

- Python 3.7+  
- pygame  
- matplotlib  

Install requirements with:

##bash
pip install pygame matplotlib

## 🧪 Virus Variants

| Variant  | Infection Chance | Mortality Rate | Immune Escape | Days to Recover |
| -------- | ---------------- | -------------- | ------------- | --------------- |
| original | 0.15             | 0.02           | 0.00          | 15              |
| variantA | 0.25             | 0.03           | 0.10          | 12              |
| variantB | 0.35             | 0.05           | 0.20          | 10              |
| deadly   | 0.40             | 0.70           | 1.00          | 12              |

## 🧬 Visual Legend

Gray: Susceptible

Red: Infected

Green: Recovered

Black: Dead

Blue: Vaccinated

Borders:

White Border: Hospitalized

Variant Borders:

Original: White

VariantA: Yellow

VariantB: Cyan

Deadly: Magenta

## 📊 Key Simulation Parameters
LOCKDOWN_THRESHOLD: 10% (Triggers lockdown)

BIRTH_RATE: 0.002 (New immune births per day per person)

HOSPITAL_EXPANSION_DAY: 30 (Hospitals gain 50 beds every 30 days)

ECONOMIC_BASE_PRODUCTIVITY: 1000 (Full productivity baseline)

## Author
Hemish Ravi
University Student

Email: Hemishdr897@gmail.com

Instagram: @hdr_hemi

LinkedIn:[ hemish-daiwik-ravi](https://www.linkedin.com/in/hemish-daiwik-ravi-023950275/)

