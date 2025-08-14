# Decision Log

- Age: filled missing with median.
- Embarked: filled missing with mode.
- Cabin: filled missing with 'Unknown'.
- Fare: capped at upper IQR limit.
- Added \*\_missing_flag columns for transparency.
- Added Fare_outlier_flag for possible model use.
