---
title: Toronto Crime Trends - Tableau
layout: post
post-image: /assets/images/tcr_geo_dist.png
description: The Major Crime Indicators (MCI) that are reported to the Toronto Police Service are analyzed and visualized as part of this project. Effective law enforcement, policymaking, and community engagement depend on an understanding of crime trends. Through the use of data visualization techniques, problems regarding the spatial and temporal distribution of crime in Toronto can be addressed, providing insights into its dynamics.Revealing the story behind crime rate indicators, take a trip through the graphics. Experience the rise and fall of criminal activity from the busy streets of cities to the quiet suburbs, and investigate the fundamental forces influencing the safety and security of our neighborhoods.

tags:
- sample
- post
- test
---

---

The objectives of this project was to decipher temporal trends, dissect spatial distributions, identify hotspots, assess prevention strategies, understand reporting efficiency and examine the influence of time on crime rates. The data cleansing and aggregation was done using python, leveraging libraries like Pandas and Numpy.The initial exploratory data analysis(EDA) helps to uncover patterns and guide further analysis in Tableau and by creating interactive visualizations that explore crime trends, spatial distributions, and temporal patterns.Insights and findings are synthesized into a Tableau poster, offering an interactive narrative guiding stakeholders through key observations.


{:target="blank"}
###### Source Code : [`Crime_indicators_toronto.ipynb`](https://github.com/hemabhaskar/Project/blob/main/Crime_indicators_toronto.ipynb)
###### Tableau Live : [`Toronto Crime trends Poster`](https://public.tableau.com/app/profile/hemalatha.bhaskar/viz/Major_Crime_Indicators/Dashboard1)
<br>

#### Year over Year trend 

<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/tcr_yoy.png" width="560" height="750" frameborder="0" allowfullscreen="">
</image>
The steady crime rates between 2014 and 2016 may be the result of stable enforcement tactics and economic conditions. Changes in law enforcement priorities or changes in socioeconomic variables may be to blame for the 2019 surge. The decline that followed in 2020 and 2021 could be brought on by pandemic-related limitations that had an impact on criminal activity. The increase in 2022 and 2023 might be a sign of shifting priorities for law enforcement or changing societal dynamics.

#### Incident category vs Division
<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/tcr_cat_div.png" width="560" height="560" frameborder="0" allowfullscreen="">
</image>
When comparing the occurrence category to the police division, it becomes clear that Division 51 has the most recorded crime counts, with around 7000 instances. Division 14 logs about 5500 events, not too far behind. In order to effectively address crime hotspots, our findings emphasize the disparities in crime occurrence between police divisions and the significance of focused law enforcement efforts and community involvement programs.

#### Incident category vs Location type
<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/tcr_cat_loc.png" width="560" height="560" frameborder="0" allowfullscreen="">
</image>
Notably, the data shows that the largest prevalence of documented crimes is found in apartments, which includes rooming houses and condos. Assault is the most common crime among the incident types, closely followed by break-ins. These results highlight the need of addressing security protocols in apartment buildings and putting policies in place to lessen assault-related crimes. Through the process of visualizing these trends, interested parties are able to identify areas of high crime and develop focused initiatives aimed at improving public safety and security.

#### Crime count vs Report delay by premises type
<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/tcr_crime_report.png" width="560" height="560" frameborder="0" allowfullscreen="">
</image>
Analyzing crime rate versus report delay by type of premises yields some intriguing findings. It is noted that outside occurrences have the shortest average delay of about 5.80 units, even though they have the greatest crime rate of almost 88,251. On the other hand, incidents related to apartments, which have 78,400 crimes reported, show an average delay that is 46.37 units higher. This implies that different types of premises may have different reporting procedures or turnaround times. In order to improve overall crime reporting efficiency and response protocols and eventually contribute to more efficient crime prevention and law enforcement methods, more research into the causes of these inconsistencies may be necessary.

#### Day vs Incident category
<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/tcr_day_inc.png" width="560" height="560" frameborder="0" allowfullscreen="">
</image>
Interesting trends can be found when event categories are analyzed at different times of the day. It has been noted that the most crimes are reported throughout the evening, with the afternoon following suit. On the other hand, crime rates are significantly lower in the morning and at night. This implies that distinct incident types are more common at particular times of the day. Law enforcement organizations and legislators can benefit from an understanding of these temporal patterns by using it to alert them of the necessity for focused patrols, surveillance, and crime prevention measures during hours of high crime. It also emphasizes how crucial it is to allocate funds and put policies into place that deal with the changing nature of crime throughout the day in order to effectively improve public safety

#### Overall Findings
The analysis of Toronto's crime landscape reveals key insights crucial for law enforcement, policymakers, and communities. Temporal patterns indicate that crimes peak during evening and afternoon hours, emphasizing the importance of targeted patrols and prevention strategies during these periods. Discrepancies in reporting efficiency by premises type underscore the need for streamlined protocols. Location-based trends highlight the prevalence of crime in apartment complexes, prompting targeted interventions. Disparities across police divisions call for tailored law enforcement efforts. Year-over-year trends underscore the impact of various factors on crime rates, urging adaptive strategies. Through data-driven approaches, stakeholders can collaboratively work towards fostering safer neighborhoods and enhancing public safety citywide.Through these data-driven approaches, stakeholders can collaboratively work towards fostering safer neighborhoods and enhancing public safety citywide.