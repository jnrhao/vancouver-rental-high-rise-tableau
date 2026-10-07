# Vancouver High-Rise Site Selection: Development Return and Rental Vacancy (Tableau)

Work in progress. This project ranks candidate sites in the City of Vancouver for a new high-rise by estimated development return, and adds the rental vacancy rate and a vacancy forecast to test whether each site's rents are likely to hold. Results are shown in an interactive Tableau dashboard.

## Business question
Under current zoning and policy, which sites give the highest development return for a high-rise, and how much does that return depend on where rental vacancy is heading?

## Planned scope
1. **Site screening**: a short list of candidate sites with the screening rules written down (zoning, site size, height and density limits, policy constraints).
2. **Development pro forma**: revenue, cost, residual land value and profit for each site, built in ARGUS Developer, with every input and its source recorded.
3. **Vacancy rate**: rental vacancy rate by neighbourhood and unit type from public data (for example, CMHC Rental Market Survey), shown as a time series.
4. **Vacancy forecast**: a forecast of the vacancy rate by neighbourhood, tested on held-out years, with the forecast error reported next to each forecast.
5. **Sensitivity**: development return under high, base and low vacancy paths, plus changes in construction cost and interest rate.
6. **Tableau dashboard**: site map, top-20 ranking, vacancy history and forecast view, and a scenario filter panel.
7. **Assumptions and limits**: a section listing every assumption and what it would change in the result.

## Status
Project started. No analysis has been completed or published yet. Results will be added to this repository as they are finished.
