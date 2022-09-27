# Python Tools

A series of tools using [Jupyter Notebooks](https://jupyter.org/) that utilize the [AerisWeather API](https://www.aerisweather.com/support/docs/api/) to download weather data and load into a [pandas DataFrame](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) for data science purposes.

Sign up for a [free developer trial](https://www.aerisweather.com/signup/developer/) to obtain your client id and client secret.

### [Fetch Current Conditions](https://github.com/aerisweather/python-tools/blob/main/conditions/conditions_download.ipynb)

This [notebook](https://github.com/aerisweather/python-tools/blob/main/conditions/conditions_download.ipynb) will allow the user to fetch current conditions for a list of locations. An optional feature allows the user to specify a list of weather attributes to include which will remove irrelevant data for that specific use case. The user also has the option to utilize a simple snippet that converts the DataFrame into a csv.

### [Fetch Historical Conditions With a Date Range](https://github.com/aerisweather/python-tools/blob/main/conditions/historical_conditions_date_range_download.ipynb.ipynb)

Use this [notebook](https://github.com/aerisweather/python-tools/blob/main/conditions/historical_conditions_date_range_download.ipynb.ipynb) when historical data for a list of locations is needed. Building on the previous example, users can provide a date range, or collection of random dates, and generate CSVs with hourly conditions for each day.

