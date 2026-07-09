# Data Professional Survey Analysis & Dashboard 📊

## 📌 Project Overview
This project involves the end-to-end data processing, transformation, and visualization of a comprehensive **Data Professional Survey** dataset. The goal of this dashboard is to extract actionable insights regarding data science careers, salaries, job satisfaction, and programming preferences. 

Designed with a strong focus on **UI/UX principles**, this interactive Power BI dashboard transforms raw survey data into a clean, intuitive, and visually engaging narrative. It highlights key metrics such as salary distributions across roles, language preferences (e.g., Python), and work-life balance satisfaction.

## 🛠️ Tech Stack & Tools
* **Data Visualization & BI:** Power BI
* **Data Transformation:** Power Query Editor
* **Calculations:** DAX (Data Analysis Expressions)
* **Dataset:** Raw Excel/CSV containing 600+ survey responses

## 🧹 Data Cleaning & Transformation (Power Query)
To prepare the dataset for accurate visualization, several data modeling and cleaning steps were performed:
* **Data Parsing:** Split and extracted combined string columns safely by duplicating and delimiting, to categorize salary brackets.
* **Aggregations:** Created custom DAX measures (e.g., `DISTINCTCOUNT` for Unique IDs) to accurately track the total number of survey takers without duplicating records.
* **Cleansing:** Handled null values, formatted data types, and streamlined redundant categories for cleaner visual representation.

## 📈 Dashboard Previews

### 1. Executive Summary & Demographics
*(Overview of the survey takers, their global distribution, and average age/salary)*
![Executive Summary](images/Screenshot%202026-07-09%20220324.png)

### 2. Salary Analysis & Role Breakdown
*(Deep dive into how salaries vary across specific data roles such as Data Scientist, Data Engineer, and Data Analyst)*
![Salary Analysis](images/Screenshot%202026-07-09%20220420.png)

### 3. Programming Preferences & Job Satisfaction
*(Analysis of the most popular programming languages—with Python taking a massive lead—and average ratings for work-life balance and salary satisfaction)*
![Job Satisfaction](images/Screenshot%202026-07-09%20220444.png)

## 💡 Key Insights Discovered
1. **Programming Language Dominance:** **Python** is overwhelmingly the favorite programming language among data professionals, making up a significant portion of the responses.
2. **Global Distribution:** The majority of respondents are based in the United States, followed by India and the UK.
3. **Salary Variations:** Data Scientists and Data Engineers command the highest average salaries compared to other roles.
4. **Satisfaction Metrics:** While work/life balance generally scores well (avg 5.74/10), there is notable variance in salary satisfaction (avg 4.27/10).

This project was built to demonstrate proficiency in data wrangling, UI/UX dashboard design, and analytical problem-solving.