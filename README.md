# Valley Fever in Kern County (2001–2023)

This project analyzes associations between Valley Fever (coccidioidomycosis) incidence in Kern County, California and environmental variables including temperature and precipitation using public datasets.

## Data Sources

- California Open Data Portal (infectious disease case counts)
- NOAA Climate Data Online (Bakersfield Airport station)

## Methods

- Filtered to Coccidioidomycosis, Kern County, Sex = Total
- Computed annual incidence rate per 100,000 population
- Aggregated monthly climate data to yearly averages/totals
- Fit quasi-Poisson regression model with population offset
- Checked and corrected for overdispersion (dispersion ≈ 285)

## Key Findings

- Temperature was not significantly associated with incidence.
- Annual precipitation showed a positive, suggestive association.
- Each additional inch of rainfall was associated with ~6.9% increase in incidence  
  (95% CI: 0.999–1.141).
- Poisson model was invalid due to extreme overdispersion, requiring quasi-Poisson correction.

## Repository Contents

- Climate datasets (NOAA)
- Valley Fever case dataset
- Generated plots visualizing trends and model results

## Author

Aiden Chea  
2026
