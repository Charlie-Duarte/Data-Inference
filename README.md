# Data-Inference
## Project Overview
This research project will attempt to answer 2 primary research questions: 
  1.  Are state issued stay-at-home orders effective and is there a causal impact on mobility by these orders? 
  2.  Can we predict the number of cases in a given US county based on various mobility metrics? For determining effectiveness, mobility metrics of states will be used to determine whether stay-at-home orders have a causal effect on people staying at their homes.

Establishing a causal relationship between stay at home orders on mobility can provide insight into the effectiveness of stay at home orders and therefore their potential as a solution or response to future pandemics / emeregency scenarios. 

To acheive our goal of predicting covid-19 cases by county, we are utilising the mobility metrics of a county as we believe there will be a strong relation between how closely a county followed stay-at-home orders (causing low or reduced mobility) and the number of cases in a county. The exact quantity predicted will be a count for the average number of cases in a given county over a given time interval. This aggregation was done to transform our variables into more gaussian-like distributions.

## Data Overview
Google 2020-2021 US Region Mobility Report
	Link: Google Mobility Dataset
	Description: Data was calculated using location tracking on google phones. It measures
in percent how much movement has changed with respect to each of the following
locations per day. This includes changes in mobility compared to a baseline for areas
such as workplaces, residential areas, retail & recreational areas, grocery stores &
pharmacies, and transit stations.
2019 County Population
Link: Census Bureau Dataset
	Description: The population per county in 2019 surveyed by the US Census Bureau.
Although the data was calculated a year before the Covid crisis, we are making the
assumption that population per county has not drastically changed in one year. This includes the population per county in the United States in 2019.
Cases By County 2020-2021
	Link:  CDC Dataset
	Description: The daily number of new Covid-19 cases per county collected by the
Center for Disease Control  in the United States from February 2020 to February 2021.
This includes the number of new daily Covid-19 cases per county.

#### RESEARCH PAPER AVAILABLE UPON REQUEST
