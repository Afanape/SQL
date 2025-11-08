# SQL-Based Analysis of Student Academic Data
📘 Project Overview

This project performs a detailed analysis of student academic data using SQL queries, stored procedures, and triggers. It demonstrates the use of SQL for extracting insights related to student demographics, parental background, attendance, and academic engagement.

The project focuses on building a structured and efficient data model that helps uncover meaningful patterns within educational datasets.

🎯 Objectives

Retrieve and summarize key academic and demographic insights.

Implement stored procedures and triggers to automate and control data operations.

Apply SQL functions for aggregation, grouping, and case-based classification.

Demonstrate data-driven insights for academic planning and policy evaluation.

🧩 Dataset Description

Table Used: student

Key Attributes:

school, sex, age, address, Parrent_status, Mother_edu, Mother_job, guardian, extra_curr_activities, family_edu_supp, traveltime, health_status, absences, etc.

Purpose: Evaluate student demographics, academic conditions, and parental background.

⚙️ SQL Techniques Implemented
🔹 Descriptive Queries

Youngest student identification.

Gender distribution across schools.

Parental living status and education levels.

Participation in extracurricular activities.

Classification of students by education level (High School, Higher Secondary, UG).

🔹 Analytical Insights

GP School recorded the highest enrollment (349 students).

354 students have parents living together.

201 students participate in extracurricular activities.

153 students lack family support, impacting educational outcomes.

The average health status of students is 3.55 on a 5-point scale.

🔹 Stored Procedures

GetStudents(reason) → Fetches all students who joined for a specific reason (e.g., course reputation).

max_travel_time() → Calculates the maximum travel time among all students.

🔹 Trigger Implementation

A BEFORE INSERT trigger validates age data, resetting out-of-range values (below 0 or above 80) to 25 for data integrity.

📈 Key Outcomes

Generated actionable insights on academic participation and demographic trends.

Designed SQL automation through procedures and triggers to maintain clean, validated data.

Demonstrated practical use of aggregate, conditional, and procedural SQL in educational analytics.

💡 Learning Highlights

Mastery of SQL query optimization, grouping, and joins.

Implementation of stored procedures for data modularity.

Understanding of data validation through triggers.

Translating raw student data into insights supporting educational decision-making.

🧰 Technologies Used

Database: MySQL / SQL Server

Tools: MySQL Workbench / DBeaver / SQL Developer

Concepts: Queries, Aggregation, Grouping, Procedures, Triggers
