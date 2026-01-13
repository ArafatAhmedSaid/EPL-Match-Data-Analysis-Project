# EPL-Match-Data-Analysis-Project

1. Project Title:

English Premier League (EPL) 2021–2022 Performance Analysis


2. Problem Statement:

Football teams generate large volumes of match data, including goals, fouls, cards, and results. However, raw data alone does not provide meaningful insights that coaches and analysts can use to improve performance. Without proper database design, structured analysis, and visualization, it is difficult to understand patterns such as home advantage, team consistency, and the impact of discipline on match outcomes.

This project aims to transform raw EPL match data into structured, analyzable insights using SQL and visualization tools. The goal is to support football decision-making by answering specific analytical questions related to performance, venue impact, and discipline.


3. Project Overview:

This project analyzes English Premier League (EPL) 2021–2022 match data using a full data analytics workflow. The data is first structured into a normalized relational database, then analyzed using advanced SQL queries in Google BigQuery. The resulting insights are visualized using interactive dashboards built in Tableau Public.

The analysis focuses on three key areas:

  a) Overall team performance and league rankings

  b) Home vs away performance comparison

  c) The impact of fouls and cards on match outcomes


4. Database Design:

The EPL dataset was structured into three normalized tables:

  a) Teams (20 teams)

  b) Matches (380 unique matches)

  c) Match Statistics (760 records, one per team per match)

Primary and foreign keys were used logically to establish relationships between teams, matches, and performance statistics. This design reduces redundancy, improves data integrity, and supports advanced analytical queries.


5. Dashboards & Insights:
  a) League Performance Dashboard:

Identifies top and bottom teams

Shows the relationship between points and goal difference

  b) Home vs Away Performance Dashboard:

Confirms the presence of home advantage

Shows teams score more and concede less at home

Helps compare venue-based performance differences

  c) Discipline Impact Dashboard:

Shows losing matches have higher fouls and cards

Indicates aggressive teams earn fewer points


6. Conclusion & Recommendations:

The analysis shows that consistent goal scoring, strong defense, disciplined play, and effective home performance are key drivers of success in the EPL. Teams that manage discipline and adapt tactics for away matches are more likely to perform better over a full season. These insights can support coaching strategies, performance reviews, and tactical planning.


7. Tools Used

  a) SQL (Google BigQuery)

  b) Tableau Public 2025.3

  c) Excel / CSV

  d) Lucidchart (for ER diagram)
