![Image](https://cdn-images-1.medium.com/max/1600/1*QHB8AhRSDDKpCV1WU1xFag.png)

|__Problem__|__Data__|__Methods__|__Libs__|__Link__|
|-|-|-|-|-|
|`Forecasting - Timeseries`|Sales|`Random Forest Regressor`|`statsmodels`, `pandas`, `sklearn`, `seaborn`|

There are stores are giving two type of promos such as radio, TV corresponding to promo1 and promo2 so that they want to increase their sales across Germany, Austria, and France. However, they don't have any idea about which promo is sufficient to do it. So, the impact of promos on their sales are important roles on their preference.

To define well-defined promo strategy, we once need to analysis data in terms of impacts of promos. In that case, since data is based on time series, we once referred to use  `time series decomposition`. After we decomposed `observed` data into `trend`, `seasonal`, and `residual` components, We exposed the impact of promos clearly to make a
