# Global Climate & Energy Transition Dataset 2025 - Data Dictionary

## Main Dataset: global_climate_energy_data_2025.csv

### Demographics & Economics
- **country**: Country name
- **region**: Geographic region (North America, Europe, Asia, etc.)
- **population_millions**: Population in millions of people
- **gdp_usd_billions**: Gross Domestic Product in billions of USD

### Energy Infrastructure
- **renewable_energy_percent**: Percentage of total energy from renewable sources
- **solar_capacity_gw**: Total installed solar power capacity in Gigawatts
- **wind_capacity_gw**: Total installed wind power capacity in Gigawatts  
- **hydro_capacity_gw**: Total installed hydroelectric capacity in Gigawatts
- **nuclear_capacity_gw**: Total installed nuclear power capacity in Gigawatts

### Energy Consumption
- **coal_consumption_mtoe**: Coal consumption in Million Tonnes Oil Equivalent
- **natural_gas_consumption_mtoe**: Natural gas consumption in Million Tonnes Oil Equivalent
- **oil_consumption_mtoe**: Oil consumption in Million Tonnes Oil Equivalent

### Environmental Impact
- **co2_emissions_mt**: Total CO2 emissions in Million Tonnes
- **temperature_anomaly_celsius**: Temperature anomaly compared to 1990-2020 average in Celsius
- **air_quality_index**: Air Quality Index (lower is better, WHO standard)

### Policy & Investment
- **renewable_investment_usd_billions**: Annual investment in renewable energy in billions USD
- **carbon_price_usd_per_ton**: Carbon pricing mechanism cost per ton CO2 in USD
- **ev_adoption_percent**: Electric vehicle adoption rate as percentage of new car sales

### Natural Resources
- **forest_coverage_percent**: Percentage of land area covered by forests
- **energy_efficiency_score**: Energy efficiency rating (0-100, higher is better)

## Projects Dataset: renewable_energy_projects_2025.csv

### Project Identification
- **project_id**: Unique identifier for each renewable energy project
- **project_name**: Official name of the project
- **country**: Country where project is located
- **energy_type**: Type of renewable energy (Solar, Wind, Hydro, Geothermal)

### Project Scale
- **capacity_mw**: Project capacity in Megawatts
- **investment_usd_millions**: Total investment in millions of USD
- **jobs_created**: Number of jobs created during construction and operation

### Timeline
- **start_date**: Project construction start date (YYYY-MM-DD)
- **completion_date**: Expected completion date (YYYY-MM-DD)
- **status**: Current project status

### Impact & Technology
- **co2_reduction_tons_annually**: Estimated annual CO2 reduction in tonnes
- **technology_provider**: Company providing the main technology
- **grid_integration**: Type of grid connection and integration

## Units and Standards

### Energy Units
- **GW (Gigawatts)**: 1 billion watts of power capacity
- **MW (Megawatts)**: 1 million watts of power capacity
- **MTOE (Million Tonnes Oil Equivalent)**: Standard unit for energy consumption

### Environmental Standards
- **Air Quality Index**: Based on WHO standards (0-50 Good, 51-100 Moderate, 101+ Unhealthy)
- **Temperature Anomaly**: Deviation from 1990-2020 baseline average
- **CO2 Emissions**: Measured in million tonnes per year

### Data Sources & Methodology
Data compiled from:
- International Energy Agency (IEA) 2025 reports
- UN Climate Change databases
- National renewable energy agencies
- World Bank climate finance tracking
- Regional grid operators

**Collection Period**: January 2025 - June 2025
**Update Frequency**: Annual with quarterly updates for project status
**Geographic Coverage**: Global (52 countries representing 85% of global energy consumption)

## Data Quality Notes
- All financial figures in 2025 USD
- Energy capacity figures as of June 2025
- Population estimates mid-2025
- Temperature anomalies calculated from 1990-2020 baseline
- Missing values indicated as 0.0 where infrastructure doesn't exist
