---
title: Data analysis - R Programming
layout: post
post-image: "https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/us_map.png"
description: 	The hierarchical cluster analysis aimed to reveal geographic patterns of cancer mortality across US states. By analyzing death rate data and computing distances, it identified clusters with similar mortality profiles. The resulting dendrogram and US map visualization illustrated hierarchical relationships and regional disparities, aiding policymakers in targeting interventions to reduce cancer mortality rates nationwide.
tags:
- jekyll
- informative
- technology
---

In the Comprehensive Health Data Analysis project for the American Health Association, spearheaded an exhaustive examination of a multifaceted dataset incorporating socio-economic, demographic, and health-related variables at the county level in the United States. By meticulously mapping the data analysis process and conducting Tidy Sanity Checks, have ensured the reliability of subsequent analysis. Thorough data cleaning, inclusive of handling duplicates and outliers, set the stage for a robust exploration of key variables through hierarchical cluster analysis. This method unveiled intricate patterns, shedding light on the socio-economic and health-related determinants influencing cancer incidence and mortality rates. The analysis underscored the pivotal role of factors such as average annual cancer counts, deaths, and socio-economic landscapes in shaping health outcomes. The project's insights have far-reaching implications for targeted cancer prevention and management strategies. My next steps involve proposing data-driven strategies for the American Health Association and delving into predictive modeling to anticipate future cancer trends. This project exemplifies my adeptness in deriving actionable insights, offering valuable contributions to public health initiatives.
{:target="blank"}
###### Source Code : [`Cancer_analysis.r`](https://github.com/hemabhaskar/Project/blob/main/Cancer_analysis.r)

## Key Steps and Analyses

### Data Analysis Process Mapping
Developed a comprehensive process map outlining the workflow for the entire data analysis project.

<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/process_map.gif" width="480" height="259" frameborder="0" class="giphy-embed" allowfullscreen=""></image>

### Tidy Sanity Checks
Ensured data tidiness by performing sanity checks to validate the structure and format.

### Data Cleaning
Conducted thorough data cleaning, including handling duplicates, addressing missing values, and identifying and managing outliers.

### Hierarchical Cluster Analysis
Utilized hierarchical cluster analysis to uncover patterns and relationships within the dataset, facilitating a deeper understanding of the socio-economic and health-related factors influencing cancer incidence and mortality rates.

In the hierarchical clustering analysis focusing on the average death rate by state, I employed a meticulous approach to distill meaningful insights. Beginning with the aggregation of death rate means at the state level, I sought to encapsulate a comprehensive overview of mortality trends. The subsequent computation of a distance matrix facilitated the understanding of the dissimilarities between states in terms of death rates. Leveraging the average linkage method, I applied hierarchical clustering, creating a dendrogram that visually depicted the hierarchical relationships among states.

To enhance interpretability, the dendrogram was segmented into six distinct clusters, each representing a cohesive group of states sharing similar death rate patterns. Adding a rectangular box to demarcate these clusters provided a clear visual guide for cluster identification. Notably, the analysis highlighted Kentucky as a state with the highest death rates, aligning it with the characteristics of cluster 6. This detailed hierarchical clustering approach not only unraveled the inherent structure within the death rate data but also offered a nuanced perspective on state-wise variations, showcasing the potential for targeted interventions and healthcare resource allocation.

<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/Dendrogram.png" width="480" height="259" frameborder="0" allowfullscreen=""></image>

<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/us_map.png" width="480" height="259" frameborder="0" allowfullscreen=""></image>

### Key Variables Analyzed

* Health Indicators
<br>Explored variables such as avgAnnCount, avgDeathsPerYear, deathRate, incidenceRate, and studyPerCap to understand cancer-related statistics at the county level.

* Socio-Economic Factors
<br>Investigated variables like AvgHouseholdSize, binnedInc, BirthRate, MedianAge, medianIncome, PctBachDeg18_24, PctEmployed16_Over, PctMarriedHouseholds, and more to assess the socio-economic landscape.

* Demographic Composition
<br>Explored variables such as PctAsian, PctBlack, PctWhite, PctPrivateCoverage, PctPublicCoverage, povertyPercent, and popEst2015 to understand the demographic composition and healthcare coverage.

### Insights and Recommendations

Identified key socio-economic and demographic factors influencing cancer outcomes.
Uncovered patterns in health indicators that can inform targeted interventions for cancer prevention and management.