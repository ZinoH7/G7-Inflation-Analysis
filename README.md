# G7 Inflation Analysis

## Description
The project investigates inflation and macroeconomic variables across G7 countries: Canada, Japan, the United States, France, Germany, Italy and the United Kingdom. 
Variables were chosen to reflect economic factors that may be associated with inflation:
- Cost push inflation (Import Prices, Oil prices)
- Demand pull inflation (GDP growth, Unemployment, Government Consumption)
- Built in inflation (Wage Growth)
- The housing market (House price growth)
- Monetary policy (Interest Rates)
- Exchange rate movements (Change in Exchange rates)

## Data
The project combines data from the following sources:

### World Bank API
- CPI inflation
- GDP growth
- Unemployment
- Money growth
- Government consumption
- Exchange rates
- Imports as a percentage of GDP

### OECD
- [House price indices](https://data-explorer.oecd.org/vis?lc=en&tm=DF_HOUSE_PRICES&pg=0&snb=1&vw=tb&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_AN_HOUSE_PRICES%40DF_HOUSE_PRICES&df[ag]=OECD.ECO.MPD&df[vs]=1.0&pd=,&dq=.Q.RHP.&to[TIME_PERIOD]=false)
- [Average annual wages, measured in USD at purchasing power parity](https://data-explorer.oecd.org/vis?tm=%22average%20annual%20wage%22&pg=0&snb=4&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_EARNINGS%40AV_AN_WAGE&df[ag]=OECD.ELS.SAE&df[vs]=1.0&dq=......&pd=2000,&to[TIME_PERIOD]=false)
- [Short-term interest rates](https://data-explorer.oecd.org/vis?lc=en&df[ds]=DisseminateFinalDMZ&df[id]=DSD_STES%40DF_FINMARK&df[ag]=OECD.SDD.STES&df[vs]=4.0&dq=AUS.M..PA.....&lom=LASTNPERIODS&lo=5&to[TIME_PERIOD]=false)

### World Bank Commodity Markets
- [Annual Crude Prices (global)](https://thedocs.worldbank.org/en/doc/74e8be41ceb20fa0da750cda2f6b9e4e-0050012026/related/CMO-Historical-Data-Annual.xlsx)
  
## Repository Structure

```text
G7-Inflation-Analysis/
|
|--- data/
|   |--- CMO-Historical-Data-Annual.csv
|   |--- OECD.ECO.MPD,DSD_AN_HOUSE_PRICES@DF_HOUSE_PRICES,1.0+all.csv
|   |--- OECD.ELS.SAE,DSD_EARNINGS@AV_AN_WAGE,1.0+all.csv
|   |--- OECD.SDD.STES,DSD_STES@DF_FINMARK,+all.csv
|   |--- panel_data.csv
|
|--- .gitignore
|--- EDA.ipynb
|--- G7_Inflation_Data_Pipeline.ipynb
|--- README.md
```
## Screenshot of Power BI dashboard
<img width="2374" height="1302" alt="image" src="https://github.com/user-attachments/assets/77d54c59-2afd-438a-9112-b104b03d9ef0" />

