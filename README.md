# Multivariate-Analysis-Course-
Learning multivariate analysis. Related assignments and project.

1. Question: whether month and other issues will influence the bus delay?

2. Reason: I take bus to school and want to find out the delay time in certain situation, which can save my time if I can adjust my schedule accordingly.
3. Data source: NJ Transit website
  Description: There are 5 columns in total. The dependent variable is delaytime, remaining 4 variables are independent.

    |NAME|TYPE|DESCRIPTION|
    |-------|-------|-----|
    |TOTAL_LATES|Numerical|total delay time of a month(dependent variable)|
    |OTP_YEAR|Numerical|2009-2023, using average to stablize the outcomes|
    |OTP_MONTH|Integer|1-12, should be changed to category|
    |TOTAL_TRIPS|Numerical|total trips of buses in a month|
    |OTP|Numerical|0~1 On Time percent|
