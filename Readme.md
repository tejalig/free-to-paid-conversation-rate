# 🎓 Course Conversion & Student Behavior Analysis
An SQL-based deep dive into the student journey: from registration to paid subscription.

## 📌 Project Overview
This project analyses the conversion funnel of an online learning platform. By querying student registration, engagement, and purchase data, I identified key behaviours that lead to paid conversions, measured the speed of the onboarding process, and analysed seasonal trends to optimise marketing efforts.

#### 🛠️ Tech Stack
Language: SQL (MySQL 8.0)

Concepts: CTEs, Window Functions, Date Manipulation, Subqueries, Joins & Aggregations.

Analysis Focus: Conversion Funnels, Time-to-Event (LTV), and User Segmentation.

## 🔍 Key Business Questions
### The Conversion Funnel 🌪️ Understanding the "leaks" in our pipeline:

Activation Rate: What percentage of students who register actually watch a video?

Engagement-to-Sale: What percentage of students who watched a video ended up buying the course?

Total Conversion: What percentage of all registered students became paid customers?

### Time-to-Event Analysis ⏱️ Measuring the "speed" of the user journey:

Onboarding Speed: The average days between registration and the first video view.

Conversion Lag: The time it takes a student to purchase after their first engagement.

### Engagement Behaviour & Lead Quality 📈 Identifying high-intent behaviours:

Retention Impact: Do students who watch videos on multiple days have a higher conversion rate than "one-hit" viewers?

Lead Quality: Comparing "Passive" users (never engaged) vs. "Active" users to determine who is more likely to convert.

Seasonality: Identifying specific months or days where registration or purchasing activity spikes.

### 📊 Insights (Summary)



📂 Database Schema
The analysis is performed across three core tables: 

 - Student_Info : Holds information about the registered students
 - Student_Engagement : Holds information about students who have watched the video at a given point in time
 - Student_Purchases : Holds the information about students who made a purchase

 The data holds information from the period of January 2021 to August 2023.


#### Findings.

##### Descrptive anlaysis:
The total number of students registered on the platform during this time were 40,979. Out of these students 20,778 of them watched videos on platform.

13% of registered students had a subscription.



