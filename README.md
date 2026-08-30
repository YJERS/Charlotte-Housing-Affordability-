# Charlotte Housing Affordability

## 1. Research Question
Which neighborhood-level factors best predict rent burden across Charlotte-Mecklenburg census tracts?

Charlotte has experienced a significant housing affordability crisis as rapid population growth has driven up rents faster than incomes. This project uses public Census data to identify which neighborhood characteristics most strongly predict housing cost stress across the county.

## 2. Data Sources
- Census ACS 5-Year 2024 (B25070, B19013, B03002, B08301, B01003)
- Charlotte Open Data Portal — NPA boundary file
- Tools: Python, pandas, scikit-learn, Folium, geopandas, matplotlib

## 3. Key Findings
- [Your insight sentence from Chart 1]
- [Your insight sentence from Chart 2]
- [Your insight sentence from Chart 3]

## 4. Model
I ran a linear regression predicting rent burden from median household income, racial composition, public transit usage, and population. Public transit access and income were the strongest predictors across census tracts.

## 5. Limitations
The model's R² was negative, indicating missing variables such as zoning policy, housing stock age, and property values likely play a significant role. Census tract level analysis cannot capture individual household variation and results reflect correlations, not causation.

