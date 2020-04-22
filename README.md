# COVID-19 US Crisis Management Analysis

[Walkthrough for County-Level Data Analysis for COVID-19 Crisis Management](https://melanieshimano.gitbook.io/merging-data-and-plotly-visualizations/).

**Business Question: Which Counties Should be Most Cautious as the COVID-19 Pandemic spreads across the US?**

For COVID-19, age is a major risk factor for severe illness and death. Older adults are at higher risk for severe illness as a result of the novel coronavirus [1](https://www.cdc.gov/coronavirus/2019-ncov/need-extra-precautions/groups-at-higher-risk.html). Additionally, children are significantly less likely to experience severe outcomes as a result of the virus[2](https://www.cdc.gov/mmwr/volumes/69/wr/mm6914e4.htm).Case fatalities are also largely dependent on external facotrs like access to proper medical care. In the wake of a global pandemic, hospitals struggle to meet the demand for beds for patients. 

This means that the counties most at risk as COVID-19 spreads across the US are ones with a higher percentage of older adults and a lower percentage of children with not enough beds to meet infection rate. 

In the chart below, the counties most at risk fall in the top left quadrant with a dark purple marker color.

![Age discrepancy and Hospitals per 100](https://github.com/CamilaCamacho/covid-19-crisis-management-analysis/blob/master/Percentage%20of%20Population%20Under%2018%20and%20Over%2060%20in%20US%20Counties.png)


The correlation table heatmap below shows the relationship between two factors. Factors sharing a yellow cell are much more likely to either increase or decrease together. Factors sharing a purple cell are likely to increase when the other decreases and vice versa.    

![COVID County Correlation Heatmap](https://github.com/CamilaCamacho/covid-19-crisis-management-analysis/blob/master/COVID19%20County%20Correlation%20Table%20Heatmap.png)
