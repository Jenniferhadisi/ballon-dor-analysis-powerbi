# 🏆 Ballon d'Or 2026 Analysis Dashboard
## Dashboard Preview
Bellow are the two pages of the interactive Power BI dashboard.
### Player Performance Dashboard
![Dashboard Overview](Images/Dashboard_overview.png)
### Final Player Ranking
![Player Ranking](Images/Player_Ranking.png)
___

## Project Overview

This project is an interactive Power BI dashboard that analyzes the performance of 20 Ballon d'Or 2026 candidates using publicly available football statistics.

The goal was to build a simple, user-friendly dashboard that allows users to explore player performance through interactive filters and visualizations. Rather than overwhelming users with advanced metrics, I focused on presenting the data in a clear and accessible way so that anyone, whether they follow football closely or not, can easily understand the analysis.

> **Note:** This ranking is **not** the official FIFA or Ballon d'Or ranking. It is a personal, data-driven ranking based on a custom scoring model created for this project.

---

## 📊 Data Preparation & Scoring Methodology

### 1. Player Performance Data

![Player Performance Ddata](Images/Player%20performance-data.png)

The player dataset contains the core performance information used in the analysis, including player, club, league, national team, minutes played, matches, goals, assists, and average rating.

This dataset formed the foundation of the analysis and was cleaned and organized in Excel before being used in Power BI.

### 2. Trophies & Achievements Data

![Trophies Data](Images/Trophies-data.png)

The trophies dataset captures collective and individual achievements for each player. These achievements were incorporated into the custom scoring model to account for success beyond individual match statistics.

---

### 3. Disciplinary Data

![Disciplinary Data](Images/Discipline-data.png)

The disciplinary dataset tracks yellow and red cards for each player. These variables were included as penalty factors in the scoring model, allowing disciplinary records to reduce a player's overall score.

---

### 4. Data Sources

![Data Sources](Images/Data-sources.png)

Player statistics for this educational project were collected from publicly available football statistics platforms, including WhoScored and StatMuse.

The sources were documented separately in the Excel workbook to maintain transparency about the data used in the analysis.

---

### 5. Custom Scoring & Ranking Model

![Ranking Data](Images/Ranking-data.png)

The prepared datasets were combined into a custom performance scoring model incorporating goals, assists, average rating, collective achievements, individual achievements, yellow cards, and red cards.

The different metrics were normalized to account for their different scales. Positive performance and achievement indicators contribute to the player's score, while disciplinary records act as penalties.

The final score was then used to rank the 20 selected players from highest to lowest.

### 🏆 Ranking Result

Based on this custom model, Harry Kane ranked first with a score of approximately 58.16, followed by Kylian Mbappé with 51.75 and Michael Olise with 48.10.

> **Disclaimer:** This project was created for educational and portfolio purposes only. The ranking is based on a custom scoring model developed for this analysis and is not affiliated with, representative of, or intended to predict the official Ballon d'Or ranking.

---

## Objective

The purpose of this project was to:

- Practice data cleaning and transformation.
- Build an interactive Power BI dashboard.
- Apply data visualization best practices.
- Create a custom performance ranking using football statistics.
- Present complex data in a simple and easy-to-understand format.

---

## Data

The analysis is based on publicly available player statistics from the 2025–2026 season, including:

- Goals
- Assists
- Matches played
- Club performance
- International team performance
- Disciplinary records (yellow and red cards)

---

## Custom Ranking Model

Instead of using the official Ballon d'Or voting process, this project uses a custom performance scoring model.

Each player receives a score based on a combination of individual and team performance metrics. The final ranking reflects the results of this model and is intended for analytical purposes only.

---

## Dashboard Features

- Interactive filters for:
  - League
  - Club
  - National Team
- Player performance comparisons
- Top 10 player ranking
- Performance overview
- Clean and easy-to-read visualizations

---

## Tools Used

- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## Skills Demonstrated

- Data cleaning
- Data transformation
- Data modeling
- Data visualization
- Dashboard design
- Performance analysis
- Interactive reporting

---

## About the Author

Hi, I'm **Jennifer Hadisi**, an aspiring Data Analyst with a background in **Business Management** and **Aviation**. This project is part of my data analytics portfolio, where I use data analysis and visualization techniques to turn data into meaningful insights. I'm currently expanding my skills in **Power BI, Excel, SQL, Python, and data visualization**, and I'm always open to learning, feedback, and new opportunities.

Thank you for taking the time to explore this project. Feedback is always appreciated!
