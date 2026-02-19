# air-quality-impact-glasgow
Data-driven analysis of air-quality, health, and economic benefits in Glasgow
## Project Overview
This project examines how improvements in air quality in Glasgow translate into
uneven, but increasingly significant, health and economic benefits as the city
moves towards net zero.

Using modelled environmental and public health data, the analysis focuses on:
- spatial differences in air-quality benefits across neighbourhoods;
- how health gains accelerate over time rather than increase linearly;
- the long-term economic value of clean-air policies.

The project emphasises data interpretation, policy impact analysis, and clear
communication of complex evidence, in line with Data Science and AI analytical
competencies.

## Research Question
How do clean transport and heating policies produce spatially differentiated
health and economic benefits in a dense, post-industrial city such as Glasgow?

## Data & Sources
The analysis is based on modelled and aggregated datasets, including:
- Climate Co-Benefits Atlas  
- Edinburgh Climate Change Institute (ECCI)  
- UK Small Area Climate Co-Benefits Model (Glasgow)  
- UK NHS health cost estimates  

## Analytical Approach
Although the final output is presented visually, the underlying work reflects
core data-science reasoning and analytical structure.

### 1. Spatial Analysis
- Neighbourhood-level comparison of an Air Quality Benefit Index  
- Identification of high-impact areas shaped by:
  - dense housing;
  - historic traffic corridors;
  - industrial urban form;  
- Visual mapping of how benefits are distributed across the city  

### 2. Time-Series Interpretation (2020–2050)
- Analysis of how air-quality benefits evolve as Glasgow approaches net zero  
- Identification of three distinct phases:
  - **Infrastructure Launchpad** – early gains from initial policy measures  
  - **Acceleration Phase** – rapid scaling of benefits as clean systems expand  
  - **Net Zero Dividend** – long-term stabilisation of health and economic gains  

### 3. Impact Ranking
- Ranking of neighbourhoods expected to gain the most from cleaner air by 2050  
- Particular focus on historically burdened areas such as:
  - Riddrie & Carntyne  
  - Castlemilk  
  - Gallowgate & Bridgeton  

## Key Findings
- Air-quality benefits are not evenly distributed and are concentrated in areas
  with historically high exposure to pollution.
- Health benefits increase faster than emissions reductions alone, as population
  exposure falls rapidly once clean systems reach scale.
- By 2050, improved air quality could generate approximately **£29.04 million per
  year** in avoided health costs for Glasgow.
- Cleaner air is associated with:
  - around **9,700 fewer hospital admissions per year**
  - approximately **726,000 fewer GP visits annually**

## Skills Demonstrated
- Data interpretation and analytical reasoning  
- Spatial inequality analysis  
- Time-series trend interpretation  
- Health economics and policy impact assessment  
- Data storytelling and visual communication  
- Translating modelled data into decision-relevant insights  

## Project Output
**Presentation:**  
`[Glasgow_Air_Quality_Health_Impact_Analysis.pdf](Glasgow_Air_Quality_Health_Impact_Analysis)

## Visuals

### Climate air quality benefits across Glasgow (spatial distribution)
![Climate air quality benefits across Glasgow](visuals/benefits-map-glasgow.png)

### Air-quality benefits rise sharply as Glasgow approaches net zero (2020–2050)
![Air-quality benefits over time 2020-2050](visuals/benefits-over-time-2020-2050.png)

### Top 5 neighbourhoods gaining most from cleaner air by 2050
![Top 5 Glasgow neighbourhoods gaining most from cleaner air by 2050](visuals/top5-neighbourhoods-2050.png)

### Total air-quality benefit for Glasgow in 2050
![Total air-quality benefit for Glasgow in 2050](visuals/total-benefit-2050.png)


## Relevance to Data Science & AI
This project demonstrates the ability to:
- work with modelled datasets
- interpret multi-variable outputs
- link environmental data with health and economic outcomes
- communicate findings clearly to non-technical audiences

These skills are directly applicable to:
- Data Analyst roles  
- Junior Data Scientist roles  
- Climate and ESG analytics  
- Public-sector and policy-focused AI applications  

## Future Development
Planned extensions of this work include:
- reproducing the analysis using Python (pandas, geopandas)
- conducting exploratory data analysis (EDA) on raw neighbourhood datasets
- developing predictive models for high-risk areas under alternative policy scenarios
- automating spatial visualisations and impact dashboards
