# Home Sales

## Overview

Run on Google Colab, this analysis of "home_sales.csv" is used to evaluate and compare the data processing efficiency and runtime of querying. The comparison will include, Spark (baseline), Spark cache and Spark Parquet. Although, with +33,000 rows, this dataset is not considered "big data", which is in upwards of millions of rows, a preliminary conclusion can still be made. 

## Results

* Spark runtime: 0.78 seconds
* `Spark cache runtime: 0.42 seconds`
* Spark parquet runtime: 0.45 seconds

## Summary

The results demonstrate, Spark cache is `46.5% faster` then using Spark alone, and `7.5% faster` than Spark parquet. Spark cache has a significant advantage in data processing efficiency when compared to its counterparts. 

However, it is to be determined which of the three approaches will have the best efficiency in querying. Only testing with diverse big datasets can a concrete conclusion be reached. 