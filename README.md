# Abstract:
**Introduction:** 
We are living in a critical era as the numbers of the new COVID_19 cases and death due to COVID-19 are increasing worldwide and in the US. So far COVID-19 cases are approximately [73 million worldwide including 16 million cases in the United States](https://coronavirus.jhu.edu/map.html). [Mask wearing as part of the social distancing methods](https://www.cdc.gov/coronavirus/2019-ncov/prevent-getting-sick/cloth-face-cover-guidance.html) is recommended as to subside the spread of this virus. However, [twelve states in the US have very limited mask wearing requirements and South Dakota has absolutely no requirement](https://masks4all.co/what-states-require-masks/). This project evaluated the effect of mask wearing policy on COVID-19 burden (i.e. new cases and new deaths). The data from two neighbor states (Georgia and Alabama) with different mask wearing policies where considered to minimize the effect of confounding factors (e.g. weather, demographics). Geowillrgia has a very limited policy only for certain employees while Alabama required mask wearing from July 17th.

<br>

**Methods:** 
All the analysis was done on the subset of the data from July 17th to November 11th. The number of new cases and new deaths were normalized to the population in each state and all the statistics and models were run on the normalized data. 

<br>

**Results:** 
The mean of new daily new cases is higher in Alabama (253.6 daily new cases per 1,000,000) compared to Georgia (195.2 daily new cases per 1,000,000) contrary to what was expected. However, the mean of new daily deaths is less in Alabama compared to Georgia (3.4 vs. 4.6 cases per 1,000,000 respectively).Timeseries graphs for daily new cases does not show that trend of new cases had a decline in Alabama compared to Georgia, contrary to what was expected. However, daily new death graph shows that overall Alabama has lower number of deaths and the trend is more stable compared to Georgia. The results from repeated measured ANOVA shows a statistically difference between daily number of cases (F statistics: 19.684, P- value <0.001) and daily number of death (F statistics: 19.684, P-value:0.029) between Alabama and Georgia. The number of daily new death is higher in Alabama compared to Georgia contrary to our hypothesis, but number of new deaths is lower in Alabama compared to Georgia aligned with our hypothesis.

<br>

**Conclusions and implications:** 
In conclusion the findings from this research support the hypothesis that mask wearing policy could be associated with lower number of death but not cases of COVID-19. Even though no causality can be inferred, but results support advocating for mask wearing policies to decrease the burden of COVID-19. 

<br>

![Graph 1](dibay/mask-wearing-policy-COVID-19-burden/new-case-trend.png)

<br>
# Source and link to the data:
https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36

Some of the variables in this dataset that  were for this analysis are as follow:

|      |Variables   | Description|
|------|------------|------------|
|      | state |Jurisdiction|
|      | submission date |Date of counts|
|      | new_casw |Number of new cases|
|      | new_death| Number of new deaths|

# Licence:

https://www.usa.gov/government-works



