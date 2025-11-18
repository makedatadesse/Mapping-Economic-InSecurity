# Mapping-Economic-InSecurity
To map average income for individuals who are working per county + the minimum budget required to live within said county

<img width="1068" height="632" alt="Screenshot 2025-11-18 at 2 50 35 PM" src="https://github.com/user-attachments/assets/5b796630-4b48-4f3a-8b3c-4acede98fe52" />

#### Analysis + Impact:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The EPI budget calculator takes into account the cost of transportation, child care, taxes, food, housing, and health care. From pure observation, there isn’t a clear correlation pattern – some red counties (high cost of living, low income) are directly next to blue counties (low costs of living and high income). Patterns don’t follow rural versus urban environments, state or county political affiliation, or even clear and strong racial demographic concentrations (one hypothesis was counties with present and active Indigenous Reservations but there was some difficulty placing this spatial data within this map).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Interestingly, many articles reference the cost-of-living crisis as a public health issue (globally and domestically) more often than as an economic issue. This is supported by numerous studies over decades on the impacts of income inequality on health and wellness, and the effect of economic disparity for some impacting the broader economic well-being of a larger population; even if not felt as early or for as long, all people in any community will feel the ramifications of some living in insecurity.

#### _Limitations:_
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This map doesn’t take into account areas with high levels of income disparity. Many of the highest metropolitan cities are within counties that show high levels of both minimum budget and mean income. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; New York County (Manhattan), for example, has both the highest concentration of wealth in the US, while being amongst the top 10 for cities with the highest income disparity (1 in 5 New Yorkers live below the poverty line). Because of this, those in the top percent with the most concentrated wealth are likely skewing mean incomes for all of New York County.
Further design for a map that improves upon analysis on the strength of these differences given income disparity would be incredibly more accurate in storytelling.

<img width="400" height="391" alt="Screenshot 2025-11-18 at 2 51 26 PM" src="https://github.com/user-attachments/assets/df387155-a16c-47b6-87c4-82e58fb4d3a7" />

#### Data Sources:
- EPI Family Budget Calculator
  - EPI guide to family budget calculator
  - (Cleaned dataset: 1 person, 0 Children)
- US Census 2023 Mean Income, Nonfamily household (Pulled in R using Census API and exported as csv)
