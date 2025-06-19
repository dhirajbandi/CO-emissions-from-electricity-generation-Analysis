# CO Emissions from U.S. Electricity Generation 🌎

## Overview
This project examines greenhouse gas emissions from the U.S. electric power sector. Using SQL queries in **Google BigQuery**, the analysis explores long‑term CO₂ trends by state and producer type. A Jupyter notebook documents the queries and resulting charts.

## Dataset 📊
The analysis relies on the [Energy Information Administration (EIA) electric power industry emissions dataset](https://www.eia.gov/electricity/data.php#elecenv). The raw CSVs were loaded into BigQuery for easier querying. The dataset covers 1990–2023 and provides yearly CO₂, SO₂ and NOₓ emissions for every state, categorized by energy source and producer.

## How to Run ▶️
1. Open the `co-emissions-analysis.ipynb` notebook.
2. Update the BigQuery project and dataset references if needed.
3. Execute the SQL cells to reproduce the queries and charts.

BigQuery was used for all data aggregation. The notebook contains detailed comments on each step.

## Results Summary 📈
- **Texas** is consistently the largest CO₂ emitter, reflecting its heavy reliance on fossil fuels.
- National emissions have declined since the 1990s as coal is replaced by natural gas and renewables.
- Indiana, Ohio and Pennsylvania show sharp drops beginning around 2010 as coal plants are retired.
- Florida’s emissions remain relatively steady until a slower decline after 2008.

Overall, the U.S. electric power industry shows progress in reducing CO₂ output, but Texas remains a key driver of national totals.

## Future Work 💡
Possible extensions include:
- Calculating per‑capita emissions by state.
- Forecasting emissions using time‑series models.
- Building interactive dashboards or mapping tools to explore spatial trends.
- Expanding the analysis to other greenhouse gases or linking to energy production data.
