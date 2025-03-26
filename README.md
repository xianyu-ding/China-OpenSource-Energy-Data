# China-OpenSource-Energy-Data

# 📚 China Energy System Modeling – Data Sources Overview

This document summarizes all key open and publicly available data sources useful for modeling China’s energy system. It includes renewable potentials, electricity demand, cost assumptions, energy balances, time-series load, and international databases.

---

## 🔋 Renewable Energy Potential

| Source | Description | China Coverage | Access | License |
|--------|-------------|----------------|--------|---------|
| [Global Wind Atlas](https://globalwindatlas.info) | High-res wind speed & power density | ✅ Yes | Online map & data download | CC BY 4.0 |
| [Global Solar Atlas](https://globalsolaratlas.info) | Global horizontal/beam irradiation & PV output | ✅ Yes | Online map & data download | CC BY 4.0 |
| [GENeSYS-MOD](https://github.com/openmod-initiative/GENeSYS-MOD) | Renewable potential, tech costs, demand for China | ✅ Yes | GitHub repository | Open |
| [Renewables.ninja](https://www.renewables.ninja/) | Hourly wind/PV capacity factors | ✅ Yes | Web interface/API | CC BY-NC (non-commercial) |
| [IRENA Resource Maps](https://www.irena.org/statistics) | Global resource assessment, incl. China | ✅ Yes | IRENA website | CC BY 4.0 |
| [China Biomass Dataset (Tsinghua)](https://doi.org/10.1038/s41597-023-02227-7) | 1km resolution agricultural & forestry biomass | ✅ Yes | Scientific Data / Figshare | CC BY 4.0 |

---

## ⚡ Electricity Demand & Load Data

| Source | Description | China Coverage | Access | License |
|--------|-------------|----------------|--------|---------|
| [Zenodo – 2018 Hourly Load (Ruggles et al.)](https://zenodo.org/record/3665573) | National hourly electricity demand (2018) | ✅ Yes | Zenodo | CC BY 4.0 |
| [CEC (China Electricity Council)](http://www.cec.org.cn/) | Annual/monthly power production, capacity, demand | ✅ Yes | CEC website | Partial (report PDFs) |
| [IEA China Reports](https://www.iea.org/reports/china-power-system-transformation) | Power demand projections & policy insights | ✅ Yes | IEA website | Limited (report-based) |
| [Guangxi Residential Load Dataset](https://doi.org/10.1038/s41597-025-04766-7) | Hourly community load from 10 cities | ✅ Yes | Scientific Data | CC BY-NC-ND (non-commercial) |

---

## 💰 Cost Assumptions (CAPEX/OPEX, LCOE)

| Source | Description | China Coverage | Access | License |
|--------|-------------|----------------|--------|---------|
| [IRENA Cost Database](https://www.irena.org/costs) | Global CAPEX, LCOE, incl. China-specific data | ✅ Yes | IRENA | CC BY 4.0 |
| [GCAM Model](https://github.com/JGCRI/gcam-core) | Global energy model, tech cost assumptions | ✅ Yes | GitHub | Open |
| [NREL ATB](https://atb.nrel.gov/) | Global tech cost benchmarks (US-focused) | ⚠️ Partial | NREL | CC BY 4.0 |
| [CREO Reports](http://www.efchina.org/Reports-en) | China Renewable Energy Outlook (tech & scenario costs) | ✅ Yes | EF China | Limited (PDF) |
| [Open Energy Platform](https://openenergy-platform.org/) | Cost datasets for energy modeling | ✅ Yes | OEP website | Open |

---

## 📊 Statistical & Energy Balance Data

| Source | Description | China Coverage | Access | License |
|--------|-------------|----------------|--------|---------|
| [National Bureau of Statistics](https://data.stats.gov.cn) | Energy production, consumption, balance tables | ✅ Yes | Official database (in Chinese) | Public, needs citation |
| [China Energy Statistical Yearbooks (CNKI)](https://data.cnki.net/) | Detailed energy data by sector & province | ✅ Yes | CNKI platform (login required) | Paid / Limited |
| [CEADs – Carbon Accounting Database](https://www.ceads.net/) | Provincial energy balance and emissions | ✅ Yes | Free registration | Open (for research) |
| [World Bank Energy Data](https://data.worldbank.org) | Electricity use per capita, GDP, macro indicators | ✅ Yes | Open Data Portal | Open |
| [Global Energy Observatory](http://globalenergyobservatory.org/) | Power plant & grid infrastructure info | ✅ Yes | GEO website | Open |

---

## 🌐 International Models & Platforms

| Source | Description | China Coverage | Access | License |
|--------|-------------|----------------|--------|---------|
| [OpenMod Initiative](https://openmod-initiative.org/) | Collaborative platform for open energy modeling | ✅ Yes | Website | Open |
| [Open Power System Data](https://open-power-system-data.org/) | Data workflows, methodology (Europe-based) | ⚠️ Not China, methods applicable | Website | Open |
| [Enerdata Yearbook](https://yearbook.enerdata.net/) | Country energy profiles, forecasts | ✅ Yes | Website (partial open) | Mixed / Some paywalled |
| [IEA Data & Reports](https://www.iea.org) | Reports and projections for China | ✅ Yes | IEA | Partial (PDFs) |
| [China Energy Portal](https://chinaenergyportal.org) | Translated energy policy, stats (EN/CN) | ✅ Yes | Open portal | Open / Volunteer-based |

---

## ✅ Notes

- All sources are meant for research, modeling, or policy work.
- Always check the license before using for commercial or derivative work.
- For time-series generation, tools like Renewables.ninja + ERA5 or CMIP6 climate data can be combined.
- Chinese platforms like CNKI or NBS may require Chinese language navigation or local assistance to access data.

---
