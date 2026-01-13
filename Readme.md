# 🎓 Course Conversion & Student Behavior Analysis
An SQL-based deep dive into the student journey: from registration to paid subscription.

## 📌 Project Overview
Analyze the transition of 40k+ users from registration to active engagement and paid subscription to identify key conversion drivers.

#### 🛠️ Tech Stack
Language: SQL (MySQL 8.0)

Concepts: CTEs, Window Functions, Date Manipulation, Subqueries, Joins & Aggregations.

Analysis Focus: Conversion Funnels, Time-to-Event (LTV), and User Segmentation.

## 🔍 Key Business Questions
### The Conversion Funnel 🌪️ Understanding the "leaks" in our pipeline:
We tracked the user journey across three main stages: Acquisition, Activation, and Retention.

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



#### 📂 Database Schema
The analysis is performed across three core tables: 

 - Student_Info : Holds information about the registered students
 - Student_Engagement : Holds information about students who have watched the video at a given point in time
 - Student_Purchases : Holds the information about students who made a purchase

 The data holds information from the period of January 2021 to August 2023.


#### 🔍 Findings

##### Key Performance Indicators (KPIs)
* **Total Registrations:** 40,979
* **Activation Rate:** 50.7% (Registered students who watched a video)
* **Engagement-to-Purchase Rate:** 13.51% (Active students who bought a subscription)
* **Total Conversion Rate:** 7.65% (Total leads turned into customers)



