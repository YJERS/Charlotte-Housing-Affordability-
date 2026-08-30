# Charlotte Housing Affordability

## 1. Research Question
Which neighborhood-level factors best predict rent burden across Charlotte-Mecklenburg census tracts?

Charlotte has experienced a significant housing affordability crisis as rapid population growth has made rents skyrocket, especially faster than incomes can handle. This project uses public Census data to identify which specific characteristics most strongly predict housing cost stress across the metro area.

## 2. Data Sources
- Census ACS 5-Year 2024 (B25070, B19013, B03002, B08301, B01003)
- Charlotte Open Data Portal — NPA boundary file
- Tools: Python, pandas, scikit-learn, Folium, geopandas, matplotlib

## 3. Key Findings
- The majority of Charlotte-Mecklenburg census tracts have between 35% and 55% of households rent burdened, with the average tract sitting at around 40%, showing that nearly half of renters across most neighborhoods are spending more than 30% of their income on housing.
- Census tracts with the lowest median incomes around $40,000 show rent burden rates approaching 75%, while the wealthiest tracts above $200,000 rarely exceed 30%, which is a gap that suggests income is the single strongest driver of rent stress in Charlotte.
- Race isn’t the most reliable predictor of rent burden, but the data shows slight negative associations for White residents and Asian residents (lower rent burdens) and slight positive associations for Black residents and Hispanic residents (higher rent burdens). 


## 4. Model
I ran a linear regression predicting rent burden from median household income, racial composition, public transit usage, and population. Public transit access was in particular the strongest predictor of rent burden across all of these census tracts.

## 5. Limitations
The model's R² was negative, indicating missing variables such as zoning policy, housing stock age, and property values likely play a significant role. Census tract level analysis cannot capture individual household variation and results reflect correlations, not causation.

