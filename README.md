Voting Behavior in the UN General Assembly
==================
In this project, I analyze all voting records from the UN General Assembly for 1946 - 2017 to see how often each country voted together with the United States on each resolution. I then compare each country's voting record to the amount of foreign aid that the country received from the US State Department. Surprisingly, foreign aid had virtually zero effect on a country's voting behavior. Even after adjusting for inflation, recency bias, and country demographic variables, spending billions of dollars in foreign aid did not have any statistically significant tendency to make countries more likely to agree with the USA in the General Assembly. Instead, countries were more likely to vote with the USA if they shared baseline economic indicators in common with the USA, such as a high GDP per capita, relatively low levels of economic inequality, and smaller levels of exports as a share of the country's total economy.

Overview of US Foreign Aid
=====================
As shown in the images below, most countries have received between $10 million and $10 billion in foreign aid since the UN was founded, with a dozen countries receiving no aid at all and a handful of tiny countries (e.g. Palau) that received only about $100,000 in aid.

![](https://github.com/JGreenLowe/UnitedNations/blob/master/images/Aid-by-Country.png)

The total amount of foreign aid distributed by the US State Department in any given year has fluctuated sharply, with peaks in the late 1940s (as part of the Marshall Plan), the late 1960s (as part of the Peace Corps), and the late 2000s (as part of the US response to terrorism).

![](https://github.com/JGreenLowe/UnitedNations/blob/master/images/Aid-by-Year.png)

Voting Patterns over Time
=================
I have graphed voting alignment with the US on a scale of 0.0 - 4.0, where 0 represents perfect agreement with the USA on all votes, 1 represents indifference to the US agenda, e.g. constantly abstaining on all votes, and 4 represents perfect disagreement with the USA, e.g., always voting 'yes' when the US votes 'no', and vice versa. Using this scale, we can visualize the popularity of the US agenda in the UN General Assembly over time. The most striking trend in this graph is that as new countries entered the UN during the 1970s and 1980s as a result of decolonization, they tended to vote strongly against the USA, adding a thick band of circles to the top edge of the graph in the 2.0 - 3.2 range (indicating strong disagreement). Another, thinner band appears in the 1990s in the 1.0 - 2.0 range, suggesting only mild disagreement from countries created as they exited the former Soviet Union. 

![](https://github.com/JGreenLowe/UnitedNations/blob/master/images/Votes-by-Year.png)

Principal Component Analysis
================
Using Principal Component Analysis (PCA), it is possible to summarize the votes of countries on thousands of different resolutions in only two dimensions so that the countries' political positions can be depicted on a two-dimensional graph. Although these dimensions are purely abstract and do not correspond to, e.g., the traditional "left/liberal vs. right/conservative" maps used by political scientists, it is nevertheless possible to identify distinct trends in the data. Countries near the top of the graph tend to be highly developed, rich, and democratic (e.g. Austria, Canada, Netherlands). Moving clockwise around the circle, countries in the top-right hand corner are hawkish and democratic (e.g. UK, Israel, USA). Countries on the far-right side of the graph include many "rogue states" such as Iran and North Korea. Countries in the left-hand side of the graph are less developed and are often former colonies. Countries in the right-hand side of the graph include many so-called "rogue states," such as Iran and North Korea. Countries near the bottom of the graph are typically poor, and many of them are island nations. Countries in the bottom-left corner of the graph tend to be majority-Arab or Communist states. Countries in the far-left edge of the graph are mostly from Latin America. Finally, there is a cluster of countries in the top-left corner that are all former Soviet republics, and then continuing on clockwise brings us to a small cluster of countries who have recently experienced a debt crisis or bailout, such as Greece, Spain, Iceland, and Ireland.

![](https://github.com/JGreenLowe/UnitedNations/blob/master/images/Votes-by-Country.png)
