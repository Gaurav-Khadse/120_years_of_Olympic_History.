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

Using MySQL Workbench, I explored trends across countries such as Finland, China, Norway, Netherlands, USA, and Denmark. The dataset covers both Summer and Winter Olympics, offering a wide range of comparative analysis opportunities.

From medal distributions to athlete participation trends, this project touches on both historical and performance-based aspects of the Olympics. Working with such a dataset not only enhanced my SQL proficiency but also helped me develop domain knowledge in sports analytics and data storytelling.

Throughout the project, I used SQL's built-in functions and filtering techniques to explore Top-performing athletes and countries, Gender-wise distribution and evolution over time, Physical attributes (Height, Weight, Age) of medal-winning athletes, Event participation frequency and medal outcomes,Missing or null value handling for better data integrity.The visual and interactive nature of MySQL Workbench added to the analytical experience by enabling query optimization and pattern discovery through real-time feedback.

This journey helped me sharpen my logical thinking, improved my ability to work with large datasets, and boosted my confidence in drawing insights from structured data. The Olympic Athletes Data Analysis Project demonstrates how SQL can be applied beyond business — into sports, history, and performance forecasting.

Don't forget to follow and star ⭐ the repository if you find it valuable.

Tools Used🛠️:My Sql Workbench

## 💾 Data Setup in SQL Workbench
The dataset was imported into MySQL Workbench. Key fields included:

ID: Unique identifier for each record

Name: Athlete’s name

Sex: Gender of the athlete (M/F)

Age: Athlete’s age

Height and Weight: Physical attributes

Team: Country or team name

NOC: National Olympic Committee code

Games: Edition of the Olympics

Year and Season: Year and type (Summer/Winter)

City: Host city

Sport and Event: Type of sport and specific event

Medal: Medal won (Gold/Silver/Bronze/NA)

SQL queries were used to filter, group, and sort this data to extract meaningful historical and comparative insights.

🔍 Exploring the Dataset
Initial exploration steps:

Using SELECT * FROM olympics_data LIMIT 5; to preview sample records

Checking gender-based participation trends in different years

Identifying athlete records with missing data in Height, Weight, or Medal fields

Exploring popular sports by athlete count

Viewing Olympic participation history for specific athletes (e.g., Paavo Nurmi or John Aalberg)

Analyzing country participation over decades

This phase ensured data understanding and readiness for deeper analysis.

🔍 Analytical Insights
Advanced queries and Python visualization revealed:

Most common sports in Summer vs. Winter Olympics

Medal-winning athletes by country (USA, FIN, NOR, NED, CHN)

Multiple entries by athletes across years and events

Identifying top-performing countries by sport

Trend of physical attributes (height, weight) for medalists

Longitudinal study of athlete performance like Paavo Nurmi (Finland – multiple medals in Gymnastics)

Gender participation over time and medal share





