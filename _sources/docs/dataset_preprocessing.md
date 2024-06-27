# Dataset and Preprocessing
In order to fuel the debate on minimum wage in the Netherlands, we have gathered different data such as:

- Minimum wage data in the Netherlands
- Percentages of people working for minimum wage in the Netherlands
- Consumer spending in the Netherlands
- Unemployment rate in the Netherlands
- Minimum wage data worldwide
- GDP (PPP) per capita, worldwide

We gathered these data from databanks such as [CBS Statline](https://opendata.cbs.nl/statline/) and [Macrotrends](https://www.macrotrends.net/).

For most datasets we removed unnecessary variables and data instances, to ensure the fastest performance when generating the visualization components. We merged the datasets which we wanted to compare, after making sure that the data alignment and integration were accurate and appropriate. 

## Variable descriptions

- Continuous / Ratio variables: `Unemployment Rate (%)`, `total_jobs`, `minimum_wage_jobs`, `percentage_minimum_wage`, `minimum wage per month (dollar)`, `minimum wage per hour (dollar)`, `GDP per capita, PPP`
- Discrete / Ordinal Variables: `ages`
- Discrete / Nominal Variables: `Entity` (country)
- Discrete / Interval Variables: `year`