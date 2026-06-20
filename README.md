# Data Analyst Job Market Analysis (SQL)

## Introduction

This project analyzes real-world job posting data to understand the current Data Analyst job market.

The goal of this project is to identify:
- Highest paying Data Analyst opportunities
- Most demanded skills for Data Analysts
- Skills associated with higher salaries
- The most optimal skills to learn based on both demand and salary

This analysis was completed using SQL and PostgreSQL.

The SQL queries used for this project can be found in the [project_sql](./project_sql) folder.
---

# Background

As someone interested in Business Intelligence and Data Analytics, I wanted to explore what skills and qualifications are valuable in the current job market.

This project helped me practice using SQL to answer real business questions by analyzing job postings, salaries, locations, and required skills.

---

# Questions I Wanted To Answer

1. What are the highest paying Data Analyst jobs?
2. What skills are required for the highest paying Data Analyst positions?
3. What skills are most demanded in remote Data Analyst jobs?
4. Which skills have the highest average salaries?
5. Which skills provide the best combination of demand and salary?

---

# Tools Used

- **SQL** - Used for querying and analyzing the dataset
- **PostgreSQL** - Database management and data storage
- **Visual Studio Code** - Writing and running SQL queries
- **Git & GitHub** - Version control and project documentation

---

# Analysis

## 1. Top Paying Data Analyst Jobs

### Objective:
Identify the highest paying Data Analyst roles available remotely.

### Approach:
Filtered Data Analyst jobs where:
- Location was set to "Anywhere"
- Salary information was available

Sorted results by salary in descending order to find the highest paying positions.

### Skills Used:
- SELECT
- WHERE
- ORDER BY
- LIMIT
- JOIN

---

## 2. Skills Required For The Highest Paying Jobs

### Objective:
Find the skills associated with the highest paying Data Analyst roles.

### Approach:
Created a CTE to first identify the top paying jobs, then joined the job postings table with the skills tables to find required skills.

### Skills Used:
- CTEs
- INNER JOIN
- Multiple table relationships

---

## 3. Most In-Demand Skills For Remote Data Analyst Jobs

### Objective:
Find which skills appear most frequently in remote Data Analyst job postings.

### Approach:
Counted how many times each skill appeared in remote Data Analyst positions and ranked them by demand.

### Skills Used:
- COUNT()
- GROUP BY
- JOIN
- Aggregations

---

## 4. Highest Paying Skills For Data Analysts

### Objective:
Identify which skills are linked with higher average salaries.

### Approach:
Calculated the average salary associated with each skill and ranked skills based on salary.

### Skills Used:
- AVG()
- ROUND()
- GROUP BY
- JOIN

---

## 5. Optimal Skills Based On Demand And Salary

### Objective:
Find skills that provide the best combination of job demand and salary potential.

### Approach:
Combined skill demand and average salary analysis using CTEs.

Filtered skills with enough job postings to avoid unreliable results and ranked them by salary and demand.

### Skills Used:
- Multiple CTEs
- INNER JOIN
- COUNT()
- AVG()
- Filtering

---

# Key Insights

Through this analysis, I found that:

- Technical skills play an important role in Data Analyst opportunities.
- Some skills have higher demand while others are associated with higher salaries.
- Looking at both demand and salary provides a better understanding of valuable skills.
- SQL and analytical thinking are essential skills for working with business data.

---

# What I Learned

Through this project, I improved my ability to:

- Write complex SQL queries
- Work with relational databases
- Use JOINs to combine multiple datasets
- Use CTEs to organize complex analysis
- Perform data aggregation
- Translate business questions into SQL solutions
- Analyze real-world datasets

---

# Conclusion

This project helped me understand how SQL can be used to transform raw job market data into meaningful business insights.

By analyzing salary trends, skill demand, and job requirements, I gained practical experience that aligns with Data Analytics and Business Intelligence roles.