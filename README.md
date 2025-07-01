# Access to Basic Services 🌍📊

This project analyzes global access to essential services such as clean water, sanitation, electricity, health, education, and transport. It is built on data aligned with **UN Sustainable Development Goal (SDG) 1.4.1**, which tracks the proportion of the population living in households with access to basic services.

## 🧭 Project Overview

Using the `access_to_basic_services` dataset, this project explores socioeconomic indicators across countries and regions — highlighting disparities in service delivery and basic human needs. This analysis can help guide policy decisions, development priorities, and sustainable solutions, especially in under-served regions.

The analysis includes:
- Descriptive summaries by region and income group
- Trend analysis by year
- Correlations between access to services, GDP, population size, and unemployment
- Visualizations of inequalities across countries

## 📊 Dataset Overview

The dataset contains over 1,000 records with the following key features:

| Column | Description |
|--------|-------------|
| `Region` | The region of a country (e.g. Sub-Saharan Africa) |
| `Sub_region` | The sub-region of a continent (e.g. Western Africa) |
| `Country_name` | Country name |
| `Time_period` | Year of the observation |
| `Pct_managed_drinking_water_services` | % of population with access to managed drinking water |
| `Pct_managed_sanitation_services` | % of population with managed sanitation services |
| `Est_population_in_millions` | Estimated population (millions) |
| `Est_gdp_in_billions` | Estimated GDP (USD billions) |
| `Land_area` | Country size in km² |
| `Pct_unemployment` | % of population unemployed |

**Source**: [UN-Habitat SDG Indicator 1.4.1 Metadata](https://unhabitat.org/sites/default/files/2020/11/metadata_on_sdg_indicator_1.4.1_10_2020_1.pdf)

---

## 📁 Project Structure

my-ds-project/
├── data/
│ └── raw/ # Raw datasets (CSV, Excel, etc.)
├── notebooks/
│ └── access_services_analysis.ipynb # Main analysis notebook
├── scripts/
│ └── helper_functions.py # Optional Python functions
├── requirements.txt
├── .gitignore
└── README.md

---

## 🔍 Key Questions Explored

- Which regions have the lowest access to safe drinking water and sanitation?
- Is there a relationship between GDP and access to basic services?
- How does unemployment relate to access to essential infrastructure?
- Are larger countries (by land area) more or less equipped with basic services?

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy)
- Jupyter Notebook
- Matplotlib, Seaborn
- Git & GitHub

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/my-ds-project.git
cd my-ds-project


