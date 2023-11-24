**Project Report: Exploratory Data Analysis on Cricket World Cups (1975-2019)**

**Objective:**
The primary objective of this project is to conduct an exploratory data analysis on Cricket World Cup data from 1975 to 2019. 
The dataset consists of information from each World Cup, including match details, teams, venues, and outcomes. 
The project aims to import the data into a Jupyter Notebook, transfer it to a MySQL database, and perform various analyses and visualizations to uncover trends and patterns.

**1. Data Import and Database Setup:**
The initial step involved importing data from CSV files into the Jupyter Notebook.
The dataset is divided into separate files for each World Cup year (1975-2019). 
After importing, the data was transferred to a MySQL database using the SQLAlchemy library.



**2. Data Cleaning and Transformation:**
The dataset underwent cleaning and transformation processes to ensure consistency and accuracy. 
Date columns were converted to the datetime format, and data types were adjusted as needed. 
This step ensures the reliability of subsequent analyses.



**3. SQL Queries and Analysis:**
Several SQL queries were executed to extract insights from the dataset. Here are some examples:

- Query 1: Total Matches in World Cup
- Query 2: Total Matches Played at Each Ground
- Query 3: Details of the Final Match of 1983 WC
- Query 4: Matches Won by Each Team



**4. Data Visualization:**
Visualizations were created using Matplotlib and Seaborn to illustrate trends and patterns in the data. 
Examples include bar charts depicting total wins by each team, win percentages, heatmaps of match results, and distribution of matches for each country at different grounds.



**5. Key Findings:**
- Total Matches: The total number of matches played in each World Cup.
- Matches at Each Ground: Distribution of matches across different grounds.
- Final Match of 1983 WC: Details of the final match, including teams and outcomes.
- Matches Won by Each Team: Analysis of the number of matches won by each team.

**6. Conclusion:**
The exploratory data analysis provides valuable insights into the Cricket World Cup data from 1975 to 2019. 
The project successfully imported and transformed the data, executed SQL queries to extract relevant information, and visualized trends through various charts.
The findings contribute to a better understanding of the tournament's history and the performance of participating teams.

**7. Future Work:**
Future work may involve more in-depth analyses, including player statistics, team performance over specific periods, and correlation analyses between different variables.
Additionally, machine learning models could be implemented to predict match outcomes based on historical data.

This project serves as a foundation for further exploration and analysis of Cricket World Cup data, offering a comprehensive view of the tournament's evolution over the years.
