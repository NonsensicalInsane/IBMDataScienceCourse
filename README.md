# SpaceX Launch Success Analysis

## Overview
This study investigates the determinants of launch success in SpaceX's rocket endeavors. As an industry leader, SpaceX endeavors to democratize space travel. Through innovative reuse of the Falcon 9 rocket's first stage, they have significantly reduced launch costs to approximately $62 million per launch, providing a stark contrast to competitors whose costs often exceed $165 million per launch. The accurate prediction of first-stage landings is of paramount importance in determining launch expenses. This analysis harnesses publicly available data and machine learning techniques to predict the reusability of the first stage, both for SpaceX and its competitors.

## Exploration
Our investigation delves into the influence of several factors on first-stage landing success, including payload mass, launch site, number of flights, orbits, and temporal success rate trends. The primary objective is to identify the most effective predictive model via binary classification.

## Executive Summary
This research follows a rigorous methodology:

### Data Collection
Data collection is carried out through SpaceX's REST API and web scraping procedures. A critical component of data wrangling involves the creation of a success/failure outcome variable.

### Data Exploration
Data visualization scrutinizes payload characteristics, launch site dynamics, flight numbers, and temporal patterns. Moreover, SQL queries yield pivotal statistics, such as cumulative payload mass, payload mass ranges for successful launches, and the total count of successful and failed outcomes.

### Data Analysis
We meticulously assess launch site success rates and their proximity to geographic markers, concurrently visualizing sites with notable success rates and payload ranges.

### Predictive Modeling
Leveraging logistic regression, support vector machine (SVM), decision tree, and K-nearest neighbor (KNN) models, we predict landing outcomes and discern the model with the highest predictive capability.

## Key Findings

### Exploratory Data Analysis
* Success rates have demonstrated an upward trajectory over time.
* Kennedy Space Center's Launch Complex 39A (KSC LC-39A) consistently attains the highest success rate among landing sites.
* Specific orbits, namely ES-L1, GEO, HEO, and SSO, consistently achieve a 100% success rate.

### Data Visualization and Analytics
A strategic placement of launch sites in proximity to the equator optimizes Earth's rotational speed.
All launch sites are situated in coastal regions.

### Predictive Analytics
Model performances on the test set are quite homogeneous, with the decision tree model slightly outperforming its counterparts.

## Methodology
Our comprehensive approach encompasses:

* Data collection via SpaceX REST API and web scraping methodologies.
* Data wrangling, including the creation of a binary success/failure variable.
* Data exploration through visualization and SQL queries.
* Cartographic visualization using Folium to portray launch sites, outcomes, and proximity measurements.
* Dashboard creation via Plotly Dash.
* Predictive analytics utilizing a suite of models and performance evaluation.

## Conclusion
Key takeaways from our analysis include:

* Model performances are relatively consistent, with a slight advantage for the decision tree model.
* The strategic placement of launch sites near the equator and coastlines is prominent.
* A discernible positive trend is observed in launch success rates over time.
* Kennedy Space Center's Launch Complex 39A (KSC LC-39A) emerges as a standout performer.
* Specific orbits, including ES-L1, GEO, HEO, and SSO, consistently attain a 100% success rate.
* Payload mass exerts a notable influence on launch success, with heavier payloads correlating positively with success rates.
