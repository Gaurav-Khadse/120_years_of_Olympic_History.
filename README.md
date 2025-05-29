# 12_years_of_Olympic_History.

## 📑 Contents

- [**🌐 Introduction**](#-introduction)
- [**💾 Data Setup in SQL Workbench**](#-data-setup-in-sql-workbench)
- [**🔍 Exploring the Dataset**](#-exploring-the-dataset)
- [**🔍 Analytical Insights**](#-analytical-insights)
- [**⚙️ SQL Techniques**](#️-sql-techniques)
- [**📂 Data Source**](#-data-source)
- [**🛠️ Skills Demonstrated**](#️-skills-demonstrated)


Olympic Athletes Participation and Performance Analysis Project
This project involves analyzing Olympic athlete participation records across various countries and sports. The dataset provides a comprehensive view of athlete demographics, Olympic event participation, and medal performance from different nations over time.

The primary focus is to explore how athletes' age, gender, height, and weight relate to their performance, sport, and medal outcomes. By analyzing athletes from countries like the USA, Finland, China, Norway, and the Netherlands across both Summer and Winter Olympics, this project uncovers trends in athletic participation and success rates.

Using SQL for data preprocessing and Python for further exploration, this project derives insights on sports popularity, gender-based participation, country-wise medal tallies, and athlete-specific performance history.

This project helped sharpen my SQL querying skills for large and multi-dimensional datasets and demonstrated how structured data can uncover deep patterns and trends in global sporting events.

⭐ Don’t forget to star this repository if you find it helpful.

🛠️ Tools Used:

MySQL Workbench

Python (Pandas, Matplotlib, Seaborn)

📂 Dataset:

Olympic Athletes Dataset

💾 Data Setup in SQL Workbench
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





