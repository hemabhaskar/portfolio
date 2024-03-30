---
title: Immigration Dashboard - Tableau
layout: post
post-image: "https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/Sankey.png"
description: Transformed raw HR data from the Human Resources Dataset on Kaggle into a comprehensive HR Management Dashboard using Power BI. This project involved data cleaning, visualization creation, and deriving meaningful insights to empower HR decision-makers.
tags:
- sample
- post
- test
---

---

This HR Analytics Dashboard project involved meticulous data preparation, advanced modeling using Power BI, and insightful data analysis through DAX functions. The resulting visualizations brought to light key trends, such as a demographic concentration in the 30s and 40s, attrition concerns in specific departments, and the prominence of the Production department. The dashboard also revealed salary dynamics and job satisfaction insights, emphasizing the contentment of "Product Technician I." Recommendations include strategies for attrition mitigation, recruitment enhancement, and tailored department-specific interventions. With a clear focus on geographical talent management, the project underscores the importance of optimizing the salary structure and positions itself as a valuable tool for informed HR decision-making and continuous optimization.

{:target="blank"}
###### Source Code : [`Sankey_Dashboard.twbx`](https://github.com/hemabhaskar/Project/blob/main/Sankey_Dashboard.twbx)
###### Tableau Live : [`Sankey_Dashboard_Live`](https://public.tableau.com/app/profile/hemalatha.bhaskar/viz/SankeyDashboard_17117628102310/SankeyDashboard)

<br>

#### Summary

In my Tableau project, utilizing immigration data from Kaggle spanning 2004 to 2013, I constructed a Sankey dashboard illustrating migration patterns to Canada. The visualization showcases the flow of immigrants from various countries over the years, with a focus on the top five countries: China, India, Pakistan, the Philippines, and the United Kingdom.

The project began with the creation of a union with an exact copy of the original data. Calculated fields were then developed to facilitate the construction of the Sankey chart.

#### Developed calculated fields
"ToPad" to create values 1 and 49 for filling gaps.
Implemented binning to bridge the gap between the created values.
Introduced a new variable "T" to facilitate the spread of Sankey marks.
Computed running sums of immigrants divided by the total number for the start and end of the Sankey chart.
Derived a Sigmoid curve to define the curve of the Sankey chart noodles.

Building the visualization involved utilizing two dimensions, Countries and Year, to create the Sankey chart. Finally, all sheets were integrated to display the flow of immigrants from countries to years, also providing insights into the percentage of total immigrants from 2004 to 2013.

#### Overall Findings
The visualization highlights a notable trend: the percentage of total immigrants to Canada has been consistently increasing across the years. Notably, China emerges as the leading contributor, consistently supplying the largest number of immigrants to Canada throughout the analyzed period.