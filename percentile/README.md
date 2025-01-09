**Outliers were identified and removed from the [dataset](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/data) using the percentile quantile method with thresholds set at the 0.001 (0.1%) and 0.999 (99.9%) percentiles. 
This approach involves calculating the data distribution's extreme lower and upper bounds, effectively capping the values within the range that covers 99.8% of the data.**


**Values below the 0.1st percentile and above the 99.9th percentile were considered extreme outliers and excluded from the dataset to reduce the influence of anomalies, improve data quality, and enhance the robustness of further analysis.**


**This method ensures a more representative dataset by focusing on the central distribution of values while minimizing the impact of extreme deviations.**

**Solution [Here](https://github.com/Sandeepmothe/math-analytics-on-data/blob/main/removing_outliers.ipynb)**  
