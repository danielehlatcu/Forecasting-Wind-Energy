# Forecasting-Wind-Energy
This university project involves the exploration of wind energy forecasting in various scenarios. My colleague and I created a hypothetical wind energy company called "RenewaBolo" for this project. Although the scenarios we worked with are entirely fictional, we aimed to make them as realistic as possible during their development.

The project focused on forecasting the following aspects:

- Average and 10th quantile of power generated by a wind turbine: this analysis aimed to provide valuable insights into overall production and worst-case scenarios. RenewaBolo intended to acquire a wind turbine, and we employed regression models to forecast its power generation (REGRESSION_code.R). Dataset used: Data2018.xlsx
- Production frequency based on wind speed: we envisioned a situation where RenewaBolo wanted to expand into a new region and had new turbines capable of generating energy if the wind speed exceeded 5 km/h. To analyze this, we utilized classification methods such as Logistic Regression and Random Forest (CLASSIFICATION_code.R). Dataset used: MT_station_Brasil.csv
- Price of energy for the upcoming week: for this forecast, we employed time series forecasting tools to predict the price trends (TIME_SERIES_code.R)

By conducting these forecasting analyses, our project aimed to contribute to the decision-making processes of RenewaBolo and enhance their understanding of wind energy production, turbine performance, and market dynamics.

Regarding the datasets:
- Data2018.xlsx was used for the first task
- MT_station_Brasil.csv (converted in .xlsx) for the second task
- energy.xlsx for the last task
