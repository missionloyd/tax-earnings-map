# State Tax & Earnings Dashboard

State income tax calculator with ACS median earnings by occupation visualization for all 50 US states.

**Live Demo:** https://missionloyd.github.io/tax-earnings-map/app

## Usage

```bash
# View map
./run.sh
# Open http://localhost:8080
```

## What's Inside

- **50 US states** with income tax calculations
- **ACS median earnings** by occupation (full-time year-round workers)
- **interactive map** with earnings-based choropleth (color-coded by earnings level)
- **sortable table** with tax brackets, exemptions, credits, and earnings data
- **custom calculations** based on filing status and dependents

## Data Sources

- Tax Data: [Tax Foundation](https://taxfoundation.org/publications/state-individual-income-tax-rates-and-brackets/)
- Earnings: [ACS Median Earnings by Occupation](https://services.arcgis.com/P3ePLMYs2RVChkJx/ArcGIS/rest/services/ACS_Median_Earnings_by_Occupation_Boundaries/FeatureServer/0) (field B24021_001E)
- Boundaries: [ArcGIS US States Generalized Boundaries](https://services.arcgis.com/P3ePLMYs2RVChkJx/ArcGIS/rest/services/USA_States_Generalized_Boundaries/FeatureServer/0)
