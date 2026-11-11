### Mikhail Serikov

Quantitative modeller: optimization, forecasting and decision-making under uncertainty for energy markets, power systems and climate, infrastructure and financial risk.
M.Sc. Ocean and Climate Physics, Universität Hamburg; thesis on the value of learning about ocean heat uptake in a climate-economy model (GAMS, Python).

The repositories below are self-directed research studies on public data. Each README states what is observed, what is assumed and how the results were checked.

#### Energy markets and trading
- **[de-power-market-ppa](https://github.com/michaelserikov/de-power-market-ppa)** (flagship): German capture prices and PPA valuation, merit-order model, battery arbitrage, day-ahead price forecasting and battery scheduling under price uncertainty (CVaR, EVPI, VSS)
- [de-battery-multimarket](https://github.com/michaelserikov/de-battery-multimarket): a battery across aFRR capacity, day-ahead and intraday markets (MILP)
- [eu-gas-storage-valuation](https://github.com/michaelserikov/eu-gas-storage-valuation): intrinsic and extrinsic value of seasonal gas storage (LP, least-squares Monte Carlo), German storage fundamentals
- [energy-book-risk](https://github.com/michaelserikov/energy-book-risk): marks, P&L attribution, limits and VaR/ES backtests of an illustrative TTF book through the 2021-2023 crisis
- [nordic-hydro-unit-commitment](https://github.com/michaelserikov/nordic-hydro-unit-commitment): unit commitment of the German thermal fleet and water values of Norwegian hydropower (SDP)
- [de-price-forecast-service](https://github.com/michaelserikov/de-price-forecast-service): day-ahead price forecasts as a service (PyTorch, FastAPI, Docker, CI, drift monitoring)

#### Power systems, adequacy and weather
- **[de-power-adequacy](https://github.com/michaelserikov/de-power-adequacy)** (flagship): resource adequacy of the German power system across 35 weather years (LOLE, EENS, ELCC) and under CMIP6 climate change factors
- [eu-weather-years-pypsa](https://github.com/michaelserikov/eu-weather-years-pypsa): which weather year to design a renewable power system for (PyPSA capacity expansion, 40 weather years)
- [de-weather-to-power](https://github.com/michaelserikov/de-weather-to-power): day-ahead wind and solar generation forecasts from ICON, ECMWF and AIFS, priced at imbalance prices
- [de-wind-solar-nowcast](https://github.com/michaelserikov/de-wind-solar-nowcast): intraday nowcasts 15 min to 6 h ahead from live generation and station data
- [de-feeder-storage-risk](https://github.com/michaelserikov/de-feeder-storage-risk): battery or reinforcement on a medium-voltage feeder, two-stage planning with EVPI by uncertainty source
- [sweden-biomass-times-mini](https://github.com/michaelserikov/sweden-biomass-times-mini): TIMES-inspired energy system model of Sweden 2025-2050, forest biomass allocation (GAMS)
- [messageix-westeros-residual-emissions](https://github.com/michaelserikov/messageix-westeros-residual-emissions): scale-up rates and carbon removal in the MESSAGEix Westeros teaching model
- [tyndp-exit-tracing](https://github.com/michaelserikov/tyndp-exit-tracing): what happens to German transmission investments after they leave the TYNDP

#### Climate and catastrophe risk
- **[de-storm-grid-risk](https://github.com/michaelserikov/de-storm-grid-risk)** (flagship): windstorms on the German transmission grid, correlated line failures, DC power flow load shedding and the value of information for reinforcement (stochastic MILP, Benders)
- [de-windstorm-risk](https://github.com/michaelserikov/de-windstorm-risk): German windstorm loss index, extreme value statistics, CLIMADA calibration, parametric trigger basis risk
- [climate-damage-panel](https://github.com/michaelserikov/climate-damage-panel): regional damage function for weather extremes (fixed effects panel, double machine learning)

#### Credit and insurance
- **[credit-pd-report](https://github.com/michaelserikov/credit-pd-report)** (flagship): PD scorecard against gradient boosting, rating grades and validation, SQL, Excel/VBA and Power BI reporting, mortgage PD and LGD through the 2007-2010 crisis
- [motor-pricing-glm](https://github.com/michaelserikov/motor-pricing-glm): motor liability pricing, GLM against gradient boosting, large claims and premium risk under reinsurance

**Tools:** Python (pandas, NumPy, SciPy, scikit-learn, PyTorch), GAMS, Pyomo, PyPSA, HiGHS, SQL (DuckDB, PostgreSQL), Excel/VBA, Power BI, Git and GitHub Actions

[LinkedIn](https://www.linkedin.com/in/mikhail-serikov)
