# Home Sales

## Overview

Run on Google Colab, this analysis of home sales from 2010 to 2017 is used to evaluate and compare the efficiency or runtime of querying. The comparison will include, Spark, Spark cache and Spark Parquet. Although, with +33,000 rows, this dataset is not considered, "big data", which is in upwards of millions of rows, a preliminary conclusion can still be made. 

## Results

Spark runtime: 0.78 seconds
Spark cache runtime: 0.42 seconds
Spark parquet runtime: 0.45 seconds

## Summary

The results demonstrate, Spark cache is 46.5% faster than using Spark alone, and 7.5% faster than Spark parquet. Spark cache has a significant advantage in computational speed when compared to its counterparts. 

However, it is to be determined which of the three approaches will have the fastest runtime. Only testing with varying big datasets can a concrete conclusion be reached. 
