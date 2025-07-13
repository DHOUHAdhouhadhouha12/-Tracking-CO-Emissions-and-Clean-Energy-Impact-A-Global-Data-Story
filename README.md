# Global Climate & Energy Transition Dataset 2025

## Overview
This comprehensive dataset provides up-to-date information on global climate metrics and energy transition progress as of 2025. It combines country-level data on renewable energy adoption, carbon emissions, climate impacts, and major renewable energy projects worldwide.

## What's Included

### 🌍 Main Country Dataset (`global_climate_energy_data_2025.csv`)
- **52 countries** representing 85% of global energy consumption
- **20 key variables** covering energy, environment, and policy metrics
- Renewable energy capacity by type (solar, wind, hydro, nuclear)
- Carbon emissions and climate impact indicators
- Economic data including renewable energy investments
- Environmental quality metrics

### 🔋 Renewable Projects Dataset (`renewable_energy_projects_2025.csv`)
- **30 major renewable energy projects** currently under construction
- Project details including capacity, investment, and timelines
- Geographic distribution across all continents
- Technology providers and grid integration information
- Expected CO2 reduction and job creation impacts

## Key Use Cases

### 📊 Climate Research & Analysis
- Track global progress toward renewable energy targets
- Analyze correlation between economic development and clean energy adoption
- Study regional differences in energy transition strategies
- Model future emission scenarios based on current trends

### 🎯 Policy & Investment Analysis
- Compare carbon pricing mechanisms across countries
- Evaluate renewable energy investment efficiency
- Assess the relationship between policy and adoption rates
- Identify investment opportunities in emerging markets

### 🔬 Data Science Projects
- Predictive modeling for renewable energy growth
- Clustering analysis of countries by energy profiles
- Time series forecasting of emission trends
- Machine learning models for energy transition planning

## Sample Insights

- **Nordic countries** lead in renewable energy adoption (Norway: 98.5%, Iceland: 98.9%)
- **China** has the largest absolute renewable capacity but lower percentage penetration
- **Carbon pricing** varies dramatically (Denmark: $285/ton vs Russia: $5.2/ton)
- **$100+ billion** in renewable projects currently under construction globally

## Data Quality & Sources

### Methodology
- Data compiled from official government sources and international organizations
- Cross-referenced with IEA, UN Climate Change, and World Bank databases
- Quality checked for consistency and completeness
- Updated as of June 2025

### Reliability
- All financial figures standardized to 2025 USD
- Energy measurements use international standards (GW, MTOE)
- Missing data clearly indicated (0.0 for non-existent infrastructure)
- Geographic coverage represents major global economies

## Getting Started

```python
import pandas as pd

# Load the main dataset
climate_data = pd.read_csv('global_climate_energy_data_2025.csv')

# Load projects data
projects_data = pd.read_csv('renewable_energy_projects_2025.csv')

# Quick exploration
print(climate_data.describe())
print(f"Countries with >50% renewable energy: {len(climate_data[climate_data['renewable_energy_percent'] > 50])}")
```

## File Structure
```
📁 climate-energy-2025/
├── 📄 global_climate_energy_data_2025.csv    # Main country dataset
├── 📄 renewable_energy_projects_2025.csv     # Projects dataset
├── 📄 data_dictionary.md                     # Detailed variable descriptions
├── 📄 dataset-metadata.json                  # Kaggle metadata
└── 📄 README.md                             # This file
```

## License
This dataset is released under Creative Commons CC0 1.0 Universal (Public Domain). You are free to use, modify, and distribute this data for any purpose.

## Contributing
Found an error or have additional data? This dataset aims to be a living resource for the climate and energy community. Contributions welcome!

## Citation
```
Global Climate & Energy Transition Dataset 2025
Published on Kaggle, July 2025
https://www.kaggle.com/datasets/global-climate-energy-transition-2025
```

---
*Last updated: July 2025 | Next update: January 2026*
