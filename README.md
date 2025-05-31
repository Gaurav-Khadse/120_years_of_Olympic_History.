# 120_years_of_Olympic_History.

## 📑 Contents

- [**🌐 Introduction**](#-introduction)
- [**💾 Data Setup in SQL Workbench**](#-data-setup-in-sql-workbench)
- [**🔍 Exploring the Dataset**](#-exploring-the-dataset)
- [**🔍 Analytical Insights**](#-analytical-insights)
- [**⚙️ SQL Techniques**](#️-sql-techniques)
- [**📂 Data Source**](#-data-source)
- [**🛠️ Skills Demonstrated**](#️-skills-demonstrated)


The 120 years of Olympic History Data Analysis Project: In today's data-driven world, sports analytics has emerged as a powerful tool in understanding athlete performance, improving training methods, and enhancing viewer experience. This project focuses on extracting meaningful insights from a rich Olympic dataset containing information on athletes, countries, events, and medals across multiple Olympic games.

The true potential of data analysis becomes evident through this project as we dive deep into the Olympic records using SQL queries and functions like SUM(), GROUP BY, ORDER BY, DISTINCT, LIMIT, and conditional clauses. At the core, this project revolves around understanding how factors like age, gender, height, weight, and nationality correlate with performance and participation in Olympic sports.

Using MySQL Workbench, I explored trends across countries such as Finland, China, Norway, Netherlands, USA, and Denmark. The dataset covers both Summer and Winter Olympics, offering a wide range of comparative analysis opportunities.From medal distributions to athlete participation trends, this project touches on both historical and performance-based aspects of the Olympics. Working with such a dataset not only enhanced my SQL proficiency but also helped me develop domain knowledge in sports analytics and data storytelling.

Throughout the project, I used SQL's built-in functions and filtering techniques to explore Top-performing athletes and countries, Gender-wise distribution and evolution over time, Physical attributes (Height, Weight, Age) of medal-winning athletes, Event participation frequency and medal outcomes,Missing or null value handling for better data integrity.The visual and interactive nature of MySQL Workbench added to the analytical experience by enabling query optimization and pattern discovery through real-time feedback.

This journey helped me sharpen my logical thinking, improved my ability to work with large datasets, and boosted my confidence in drawing insights from structured data. The Olympic Athletes Data Analysis Project demonstrates how SQL can be applied beyond business — into sports, history, and performance forecasting.

Don't forget to follow and star ⭐ the repository if you find it valuable.

Tools Used🛠️:My Sql Workbench.

Data Set📂:[120 years of Olympic History Dataset](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

## 💾 Data Setup in SQL Workbench
The dataset was imported into MySQL Workbench. Key fields included:

- ID: A unique identifier for each athlete entry.

- Name: The full name of the athlete.

- Sex: Gender of the athlete (M/F).

- Age: The age of the athlete during the event.

- Height: Athlete’s height in centimeters.

- Weight: Athlete’s weight in kilograms.

- Team: The name of the country/team the athlete represented.

- NOC: National Olympic Committee code (e.g., FIN for Finland, NOR for Norway).

- Games: Represents the year and season (e.g., 1992 Summer, 1994 Winter).

- Year: The year of the Olympic event.

- Season: Either “Summer” or “Winter” Olympics.

- City: The host city of the Olympic Games.

- Sport: The type of sport (e.g., Gymnastics, Swimming, Alpine Skiing).

- Event: Specific event within the sport (e.g., Gymnastics Men's Floor Exercise).

- Medal: The medal won (Gold, Silver, Bronze, or NA for no medal).

These columns were analyzed using SQL queries to perform a variety of operations such as aggregation, filtering, sorting, grouping, ranking, and joins to extract insights about athlete performance, country participation, and medal achievements.

## 🔍 Exploring the Dataset
After setting up the dataset in MySQL Workbench, the initial step was to explore and understand the structure of the data. Using queries like SELECT * FROM table_name LIMIT 5;, I previewed the dataset to get a comprehensive overview of the information available for analysis.

This exploratory phase involved:


- Reviewing column names, such as Name, Sex, Age, Height, Weight, Team, NOC, Year, Season, Sport, Event, and Medal, to understand the overall schema and data coverage.

- Understanding the relationships between key attributes, like how Team and NOC connect to athlete nationality, and how Sport, Event, and Medal reflect performance data.

- Assessing demographic distributions by scanning values of Sex, Age, Height, and Weight to identify athlete characteristics across different sports and countries.

- Exploring temporal data, including the Year, Games, and City, to see patterns across different Olympic editions.

- Identifying missing values, such as NA in Height, Weight, or Medal, to determine data quality issues and plan for data cleaning or filtering.

- Highlighting recurring names to detect athletes who participated in multiple events or years.

- Analyzing the spread of medal wins and identifying which countries and athletes had repeated successes.





