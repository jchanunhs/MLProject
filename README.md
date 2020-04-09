# MLProject
Clustered Linear Regression in R
- Dataset is based on the Covid-19 pandemic and retrieved from: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
- Purpose: Used cluster linear regression to improve accuracy of predicting the future infections and deaths from the coronavirus from 3/08/2020 - 3/15/2020 based on the dataset from 1/22/2020 - 3/7/2020.

Libraries used
- Tidyverse - Sort data based on date / days
- Ggplot - linear model
- Cluster - using cluster algorithms
- Factoextra - visualize the clusters 

Dataset has 3992 rows and 8 columns.
Merged data based on the date of reported infections, death and recoveries from 1/22/2020 - 3/07/2020.


Control 
- Normal linear regression model for infected and death
Experimental
- Cluster 1: Consist of Day 1 - 22 (1/22/2020 - 2/12/2020) // 32 days away from 3/15
- Cluster 2: Consist of Day 23 - 36 (2/13/2020 - 2/26/2020) // 18 days away from 3/15
- Cluster 3: Consist of Day 37 - 46 (2/27/2020 - 3/07/2020) // 8 days away from 3/15

Results
- Normal linear model: infected(day) = 2582 * day - 7922
- Cluster 1: infected(day) = 2582 * day - 7922
- Cluster 2: infected(day) = 1468 * day + 39608
- Cluster 3: infected(day) = 2636 * day - 6158

Prediction for 03/15/2020
- Normal linear model for infections: 135192 predicted infections.
- Cluster 1 linear model: 131506 predicted infections.
- Cluster 2 linear model: 118880 predicted infections.
- Cluster 3 linear model: 136186 predicted infections.
- Normal linear model for deaths: 4427 predicted deaths. 

Actual
- Infected on 03/15/2020: 162774
- Deaths on 03/15/2020: 6460

Percent errors
- Linear model infection percent error: 17.0% 
- Cluster 1 percent error: 19.2%
- Cluster 2 percent error: 27.8%
- Cluster 3 percent error: 16.33%
- Linear model death percent error: 31.5%


