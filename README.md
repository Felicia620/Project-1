# Income & Race in New Jersey between 2015 - 2019

![101116_eLEND_15195766](https://user-images.githubusercontent.com/83233764/126723732-4ef40752-47a3-45f9-a2c1-c7e59e474851.jpg)

INTRODUCTION

Questions we asked ourselves
- What are the disparities in income between races?
- How small or large are these differences?
- Have differences in income changed over the years? How?

What?
- Gain insights on race and income 
- by zip code in New Jersey
- Income Data from Census Bureau API *American Community 5 Year Survey Data

Why?
- Long history of income inequality
- Current recession
- Social discourse of income inequality between races

CODE 
(please refer to Project 1 for ALL Code)
API Call:

<img width="938" alt="Screen Shot 2021-07-20 at 8 23 50 PM" src="https://user-images.githubusercontent.com/83233764/126723943-9fab1e9b-e0db-4148-afa2-cadc83f48f8d.png">

Merged Code:

<img width="801" alt="Screen Shot 2021-07-20 at 9 08 00 PM" src="https://user-images.githubusercontent.com/83233764/126723990-8d2fa0e1-434e-4d9b-afdc-8dc7a4f433b6.png">

<img width="807" alt="Screen Shot 2021-07-20 at 9 08 31 PM" src="https://user-images.githubusercontent.com/83233764/126724040-ffb2a62b-529c-475f-bcac-961c4ae6fea3.png">

Summation Code:

<img width="935" alt="Screen Shot 2021-07-20 at 8 18 55 PM" src="https://user-images.githubusercontent.com/83233764/126724112-e2e33be4-0e75-491a-8ef0-7aff907b1ad7.png">

Visualization Code:

<img width="806" alt="Screen Shot 2021-07-20 at 8 30 15 PM" src="https://user-images.githubusercontent.com/83233764/126724147-f97994fe-b330-437c-b08b-1b3e1decf2f0.png">

Conclusion From Visuals: Hispanic Americans’ incomes have increased by 0.9% between 2015 and 2019, White Americans’ have decreased by 1% in NJ

![AllEthnicities2015](https://user-images.githubusercontent.com/83233764/126724342-3a827580-5421-440a-b95c-730240cc5d49.png) ![AllEthnicities2016](https://user-images.githubusercontent.com/83233764/126724354-699e5c96-3db9-40f2-bab5-d14d7363391d.png) ![AllEthnicities2017](https://user-images.githubusercontent.com/83233764/126724361-eae6da8f-52f0-4ebd-a9ab-85f62d6f662c.png) ![AllEthnicities2018](https://user-images.githubusercontent.com/83233764/126724370-2af40d55-4599-487a-89c0-70ab5c4e321d.png) ![AllEthnicities2019](https://user-images.githubusercontent.com/83233764/126724379-4fee7931-5afa-4857-8888-7f813982ce95.png)

Between 2015 and 2019, White Americans had the highest earnings in NJ
- Visual aid that shows that each race did not increase or decrease significantly over 5 years in terms of their earning potential 
- White Americans make up ~60% of the population in NJ and therefore have the highest income, based on the bar chart on the left.
- White Americans as a group are an outlier in terms of income in New Jersey, based on the box plot on the right.
- Hispanic Americans earn closest to average income in New Jersey, based on the box plot on the right.

![BoxPlotTotals](https://user-images.githubusercontent.com/83233764/126724474-b8fb4ab7-b6ec-410b-b86a-71f7a3dfa239.png)
<img width="400" alt="Screen Shot 2021-07-22 at 8 21 41 PM" src="https://user-images.githubusercontent.com/83233764/126724602-f1a7ffaa-371a-4149-b660-288938f66dbf.png">

Wealthier population are located closer to metropolitan areas (ie. NYC and Philadelphia) and “The Shore”
- Higher cost of living near cities and beaches
- Larger population in city suburbs

<img width="363" alt="Screen Shot 2021-07-22 at 8 24 29 PM" src="https://user-images.githubusercontent.com/83233764/126724683-6666c565-b79b-4e07-9a44-63ff7c70debc.png">

Key:
Warmer colors corresponds to higher income
Cooler colors corresponds to lower income
No color corresponds to no data

CONCLUSION:

Hypotheses:
- Felicia: Black and Hispanic American income did not increase moderately between 2015 and 2019. The region with the highest income was beyond the Hudson County area.
- Ryan: Asian Americans do not have a plurality of income earned. They are the smallest race by population in NJ
- Peta-Gaye: Asian Americans earned the least.
- Donett: There was a positive change in total income only for Hispanic Americans. For all other groups the change in total income  was sometimes negative.
- Carlyse: Asian, Black, and Hispanic American income was at least 80% less than White Americans’.

Post Mortem:
- We didn’t recognize there was corrupt data until we created our visualizations.
- We didn’t include data on demographic size so we can’t validate our hypotheses.
- When we merged data frames, leading zeros for zip codes were unexpectedly dropped.
- Creating a concise, organized, and functional repository with several branches.

RESOURCES:

- https://www.census.gov/data/tables/time-series/demo/income-poverty/cps-hinc/hinc-01.html
- https://www.census.gov/data/tables/time-series/demo/income-poverty/historical-income-households.html
- https://developers.google.com/maps/documentation/javascript/heatmaplayer
- Python/Pandas Bar chart code/Stacked bar chart code from the following site: api.census.gov

Image arts: 
- https://www.elend.com/2016/10/11/top-10-new-jersey-counties-ranked-by-per-capita
- https://www.app.com/story/news/investigations/data/analysis/2019/01/28/rich-towns-poor-towns-nj/2525888002/
- https://www.mypaycalculator.net/us-paycheck-calculator/new-jersey/





