# Overview
- This project investigates the net migration trends between South Asian Countries like Pakistan, India, Afghanistan, Sri Lanka and Bangladesh.
- Focusing on the period from 1990 to 2023. 
- The analysis utilizes publicly available datasets to understand migration patterns and their implications on both countries.
- The data set downloaded from World Bank API, for the reliability.

# Data Sources
- The data is sourced from the World Bank, ensuring its reliability and accuracy.

# Analysis Workflow
The Jupyter notebook net_migration_project_south_asia.ipynb performs the following steps:

1. Data Loading: 
   - Imports migration data for all countries from world bank.

2. Data Cleaning: 
   - Handles missing values and ensures data consistency.

3. Exploratory Data Analysis (EDA):
   - Visualizes migration trends over time.
   - Compares net migration rates between the two countries.

4. Statistical Analysis:
   - Conducts hypothesis testing to determine significant differences in migration patterns.
5. Spike Detection:
   - Identifies periods with sudden increases or decreases in net migration.
6. Visualization:
   - Generates line plots and bar charts to illustrate findings.
# Key Findings
- Migration Trends: 
  - Both countries experienced fluctuating migration rates, with notable peaks during periods of economic or political change.
- Comparative Analysis: 
  - India's net migration rate has generally been higher than Pakistan's, indicating a greater influx of immigrants.
- Net Migration Analysis:
  - Calculate net migration and net migration rate for each country.
  - This helps in understanding **regional migration patterns:** India remains stable despite being the largest, Pakistan and Bangladesh see steady outflows, while Afghanistan reflects volatility due to conflict-driven migration.
  - Afghanistan shows the sharpest negative migration figures, largely linked to prolonged conflict, instability, and displacement.
  - Bangladesh records consistently high emigration, driven mainly by overseas labor migration, especially to the Middle East.
  - India displays relatively moderate fluctuations, reflecting both emigration (skilled workers abroad) and immigration (regional inflows).
  - Pakistan follows a similar pattern to India but with more pronounced outflows, tied to economic migration.
  - Sri Lanka exhibits smaller-scale but steady negative migration, influenced by labor migration and post-conflict diaspora movement.
- Annual Populaiton and Estimating Emigrants Analysis:
   - Calculate Annual Populaiton Change and Estimating Emigrants.
   - India:
     - Shows the highest number of emigrants throughout the period.
     - Steady increase from ~10 million in the 1960s to a peak of ~20 million around early 2000s.
     - Decline after the peak until ~2020, with a slight recovery afterward.
   - Pakistan:
     - Moderate growth in emigrants from ~1 million in the 1960s to ~5 million in recent years.
     - Shows a fairly steady upward trend, with minor fluctuations over time.
   - Bangladesh:
     - Emigration remains relatively stable, between ~1–3 million throughout the timeline.
     - Slight peaks in the late 1970s and early 2000s, then stabilizes around 2–3 million.
   - Afghanistan:
     - Low but fluctuating emigration numbers compared to India and Pakistan.
     - Peaks correspond to periods of conflict, especially in the 1980s and 2000s.
   - Sri Lanka:
     - Very low emigration numbers throughout the period, often close to zero.
     - Slight negative dips, likely reflecting net migration adjustments or data corrections.
   - Overall Trends:
     - India dominates South Asia in terms of emigrant numbers.
     - Pakistan shows a consistent upward trend, indicating increasing emigration over time.
     - Afghanistan and Bangladesh have smaller but noticeable fluctuations linked to political or economic factors.
     - Sri Lanka remains almost negligible in comparison to other countries in the region.
# Requirements
- To run the analysis locally, ensure you have the following Python packages installed.
# License
- This project is licensed under the MIT License.
