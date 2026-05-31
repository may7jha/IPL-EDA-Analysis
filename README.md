🏏 IPL Data Analysis Project
📌 Project Overview

The Indian Premier League (IPL) is one of the world's most competitive T20 cricket leagues. This project analyzes IPL match and ball-by-ball data to uncover patterns related to team performance, toss decisions, batting trends, venue impact, player achievements, and pressure situations.

The goal is to transform raw cricket data into meaningful insights using Python, Pandas, Matplotlib, and Exploratory Data Analysis (EDA).

🎯 Business Problem

What factors contribute to success in the IPL?

This project investigates:

Which teams have dominated IPL history?
Does winning the toss really matter?
How has batting evolved over the years?
Who are the greatest IPL performers?
Which venues favor high scoring?
What are the most thrilling matches in IPL history?
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
📂 Dataset
Matches Dataset

Contains match-level information:

Teams
Venue
Toss winner
Match winner
Result margin
Season
Deliveries Dataset

Contains ball-by-ball information:

Batter
Bowler
Runs scored
Wickets
Extras
📊 Analysis Performed
1️⃣ Team Dominance Analysis
Questions Answered
Which teams played the most matches?
Which teams won the most matches?
Which teams have the highest win percentage?
Key Findings
Mumbai Indians and Chennai Super Kings emerged as the most successful franchises.
Consistent teams maintained strong win percentages across multiple seasons.
2️⃣ Toss Impact Analysis
Questions Answered
How often does the toss winner win the match?
Does choosing to bat or field provide an advantage?
Key Findings
Toss advantage exists but is not decisive.
Winning the toss does not guarantee winning the match.
3️⃣ Batting Evolution Analysis
Questions Answered
How have average IPL scores changed over time?
Which seasons were the highest scoring?
Key Findings
IPL has become significantly more batting-friendly.
Recent seasons recorded the highest average team scores.
4️⃣ Highest Team Totals
Questions Answered
What are the highest team scores in IPL history?
Key Findings
Sunrisers Hyderabad recorded the highest IPL team total of 287 runs.
5️⃣ IPL Batting Legends
Questions Answered
Who scored the most runs?
What are the highest individual scores?
Key Findings
Virat Kohli leads the all-time run charts.
Chris Gayle holds the highest individual IPL score with 175*.
6️⃣ IPL Bowling Legends
Questions Answered
Who took the most wickets?
Key Findings
Yuzvendra Chahal emerged as the highest wicket-taker in IPL history.
7️⃣ Venue Impact Analysis
Questions Answered
Which venues hosted the most matches?
Which venues produced the highest-scoring games?
Key Findings
Eden Gardens hosted the most IPL matches.
Visakhapatnam recorded the highest average match score.
8️⃣ Pressure Situation Analysis
Questions Answered
Which matches had the closest winning margins?
Which matches had the largest victories?
How common are Super Overs?
Key Findings
Several IPL matches were decided by just 1 run.
IPL consistently delivers high-pressure finishes and thrilling contests.
📈 Visualizations

The project includes:

Bar Charts
Horizontal Bar Charts
Line Charts
Team Rankings
Venue Comparisons
Seasonal Trends
🏆 Major Insights
Metric	Result
Highest Team Total	Sunrisers Hyderabad – 287
Highest Individual Score	Chris Gayle – 175*
Most Runs	Virat Kohli
Most Wickets	YS Chahal
Highest Scoring Venue	Visakhapatnam
Closest Winning Margin	1 Run
🚀 Future Improvements
Predict match winners using Machine Learning
Analyze player strike rates and economy rates
Create interactive dashboards using Power BI or Tableau
Build IPL win prediction models
📁 Repository Structure
IPL-Data-Analysis/
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── images/
│   ├── team_wins.png
│   ├── toss_analysis.png
│   ├── batting_evolution.png
│   ├── highest_team_totals.png
│   ├── top_run_scorers.png
│   ├── top_wicket_takers.png
│   └── venue_analysis.png
│
├── notebooks/
│   └── IPL_Data_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore