# Data-statistics-Assignment

In this activity, We are a member of an analytics team for the United States Environmental Protection Agency (EPA). We are assigned to analyze data on air quality with respect to carbon monoxide, a major air pollutant. The data includes information from more than 200 sites, identified by state, county, city, and local site names. We will use Python functions to gather statistics about air quality, then share insights with stakeholders.

## Data Sources

Air Quality Data: The primary data set used for analysis is the  "c4_epa_air_quality.csv"  file containing detailed information about air quality of USA

## Descriptive Statistic Analysis
In this Analysis we performed following task:

1. Data loading.
2. Data Exploration.
  - 
4. Statistical tests.
5. Results and evaluation.

#### Result/Finding during Descriptive Analysis
- 75% of the AQI values in the data are below 9, which is considered good air quality.
- Funding should be allocated for further investigation of the less healthy regions in order to
learn how to improve the conditions.

## Explore probability distributions
Data set used "modified_c4_epa_air_quality.csv"

In this Analysis we performed following task:

1. Data loading.
2. Data Exploration.
   - Created a histogram to visualize distribution of aqi_log.
   - Used the empirical rule to observe the data, then test and verify that it is normally distributed.

### Result/Findings during Probalbilty Distribution analysis

- Plotting the data using a histogram, then observing the shape, enables  to visually determine whether the data is normally distributed.
- The empirical rule can be used to verify whether a distribution is normal.
- The mean and standard deviation are important measures when applying the empirical rule to a distribution.
- Z-score allows to identify potenial outliers in the data.
-  The distribution of the aqi_log data is approximately normal.
- Using statistical methods, it was determined that the site at West Phoenix has worse air quality than the other sites.
- Consider allocating more resources toward further examining this site in order to improve its air quality.

## Explore hypothesis testing
In this task we analyzeAQI data to help them prioritize their strategy for improving air quality in America.

Data set used "c4_epa_air_quality.csv"

In this Analysis we performed following task:
1. Data loading.
2. Data Exploration.
   - We have county-level data for the first hypothesis.
   - Ohio and New York both have a higher number of observations to work with in this dataset.
3. Statistical Tests
   - Formulate the null hypothesis and the alternative hypothesis.
   - Set the significance level.
   - Determine the appropriate test procedure.
   - Compute the p-value.

### Result/Findings during hypothesis testing
 1. Even with small sample sizes, the variation within the data is enough to allow  to make statistically significant conclusions. We identified at the 5% significance level that the Los Angeles mean AQI was stastitically different from the rest of California, and that New York does have a lower mean AQI than Ohio. However, we were unable to conclude at the 5% significance level that Michigan’s mean AQI was greater than 10.
 2. For each test, we would present the null and alternative hypothesis, then describe  conclusion and the resulting p-value that drove that conclusion. As the setup of t-test’s have a few key configurations that dictate how we interpret the result, we would specify the type of test we chose, whether that tail was one-tail or two-tailed, and how we performed the t-test from stats.


   




