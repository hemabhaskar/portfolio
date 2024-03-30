---
title: Immigration Dashboard - Tableau
layout: post
post-image: "https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/Sankey.png"
description: This Tableau project shows migration to Canada with a Sankey dashboard using immigration data from Kaggle from 2004 to 2013. The top five nations that send immigrants are the UK, China, India, Pakistan, and the Philippines. The Sankey chart shows the increasing percentage of total immigrants throughout time, together with the flow of immigrants, using dimensions of Countries and Year. Notably, China has been Canada's top source of immigrants on a constant basis.

tags:
- sample
- post
- test
---

---

The project began with the creation of a union with an exact copy of the original data. Calculated fields were then developed to facilitate the construction of the Sankey chart.

{:target="blank"}
###### Source Code : [`Sankey_Dashboard.twbx`](https://github.com/hemabhaskar/Project/blob/main/Sankey_Dashboard.twbx)
###### Tableau Live : [`Sankey_Dashboard_Live`](https://public.tableau.com/app/profile/hemalatha.bhaskar/viz/SankeyDashboard_17117628102310/SankeyDashboard)
<br>

#### Developed calculated fields
"ToPad" to create values 1 and 49 for filling gaps.
Implemented binning to bridge the gap between the created values.
Introduced a new variable "T" to facilitate the spread of Sankey marks.
Computed running sums of immigrants divided by the total number for the start and end of the Sankey chart.
Derived a Sigmoid curve to define the curve of the Sankey chart noodles.

Building the visualization involved utilizing two dimensions, Countries and Year, to create the Sankey chart. Finally, all sheets were integrated to display the flow of immigrants from countries to years, also providing insights into the percentage of total immigrants from 2004 to 2013.

#### Overall Findings
The visualization highlights a notable trend: the percentage of total immigrants to Canada has been consistently increasing across the years. Notably, China emerges as the leading contributor, consistently supplying the largest number of immigrants to Canada throughout the analyzed period.