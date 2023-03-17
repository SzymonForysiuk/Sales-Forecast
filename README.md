## Sales Forecast

#### Predicting weekly sales one year ahead
Our task will be to build a model that forecasts weekly sales for each store using historical data. 


**Data are three csv files: Sales, Features, Store**

**Sales** - Historical sales data.
- `store` - store number (store contains one or more branches).
- `dept` - branch number
- `date` - week (data is collected in weekly groups)
- `weekly_sales` - sales for a given department in a given store
- `is_holiday` - whether the week is a special week (holiday).


**Features** - Include additional data related to the store, department and regional activity for the given dates.

- `store` - the store number,
- `date` - the week (the data is collected in weekly groups),
- `temperature` - the average temperature in the region,
- `fuel_price` - the cost of fuel in the region,
- `mark_down1-5` - anonymized data related to promotional price reductions. Mark_down data is not available until after November 2011 and is not available to all stores at all times. Any missing values are marked "NAN".
- `cpi` - the consumer price index,
- `unemployment` - the unemployment rate,
- `is_holiday` - whether the week is a special holiday week.

**Store** - Information about the type and size of the store.


The metric for success in this task will be `Meam Absolute Error`
