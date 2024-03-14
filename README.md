This repository contains a dataset and code for predicting bike sharing demand. The dataset contains 17,414 observations of 10 variables, including timestamp, count of new bike shares, real temperature, "feels like" temperature, humidity, windspeed, weather code, holiday status, weekend status, and season. The code includes Jupyter notebooks for data exploration, preprocessing and evaluation.

London bike sharing dataset Historical data for bike sharing in London 'Powered by TfL Open Data'.

Data Dictionary: The dataset used for model building contained 17,414 observations of 10 variables. The data contains the following information:

## Data Dictionary
| Variable               | Description                                                                                               |
|------------------------|-----------------------------------------------------------------------------------------------------------|
| timestamp                | Field for grouping the data. |
| cnt           | Count of new bike shares.                                            |
| t1| Real temperature in Celsius. |
| t2   | "Feels like" temperature in Celsius.    |
| hum  | Humidity in percentage.  |
| windspeed  | Wind speed in km/h. |
| weather_code | Category of the weather.  |
| is_holiday | 1 if it's a holiday, 0 if not.   |
| is_weekend| 1 if it's a weekend, 0 if not.|
|season| Category field for meteorological seasons: 0-spring; 1-summer; 2-fall; 3-winter. |

Repository Contents:
data/: Folder containing the dataset.
scripts/: Python scripts for data preprocessing, data analysis, and evaluation.
Pdf/: A pdf of the whole script and visualizations.

List of Python packages required to run the code.
Pandas: Library for data manipulation and analysis.
Matplotlib: Library for creating visualizations in Python.
Seaborn: Data visualization library for drawing statistical graphics.

Dataset source: 
https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data

Feel free to contribute by adding new features, or exploring different algorithms.
