# Minor_project4
BingePlay — Streaming Analytics Project
📌 Project Overview

BingePlay is a fictional Indian OTT streaming platform analytics project developed as part of the 4th Minor Project in the Data Analytics & Data Science Track by Unlox Academy.

The project focuses on using SQL and MySQL to solve real-world business and product analytics problems related to subscriptions, users, streaming behavior, content performance, engagement, and churn.

The project contains 12 business questions, progressing from basic SQL analysis to advanced SQL techniques.

🎯 Objectives

The main objectives of this project were to:

Analyze BingePlay's subscription and revenue data
Understand user signup and viewing behavior
Analyze device usage and content ratings
Identify binge-watching patterns
Analyze subscription upgrades and user plans
Detect user engagement patterns
Identify potential churn signals
Practice advanced SQL techniques used in real-world analytics
🗄️ Database

The project uses a MySQL database named bingeplay containing five tables:

Table	Description	Rows
users	User information	3,000
subscriptions	Subscription history	4,497
shows	Show/content information	100
watch_sessions	User viewing sessions	100,351
ratings	User ratings	5,000

The dataset covers activity from January to June 2024.

🔍 Business Questions Solved
Tier 1 — SQL Foundations

Q1. Active Revenue
Calculated active subscriptions and monthly recurring revenue as of June 30, 2024.

Q2. Signup Momentum
Analyzed monthly user signups and identified the month with the highest number of signups.

Q3. Device Analytics
Compared sessions, watch time, average watch duration, and completion rate across devices.

Q4. Rating Distribution
Analyzed ratings from 1 to 5 stars and calculated the percentage of highly rated content.

Q5. Originals vs Acquired Content
Compared BingePlay Originals with acquired content based on show count, IMDb rating, and release year.

Tier 2 — Joins & Subqueries

Q6. Binge Day Detection
Identified users watching the same show at least five times on the same day.

Q7. Q1 Signups Who Never Watched
Found users who signed up during Q1 2024 but never watched a session, while correctly handling NULL values.

Q8. Over-Paying Premium/Family Users
Identified Premium and Family users whose viewing history consisted only of Basic-tier content.

Q9. Upgrade Success Cohort
Identified January signups who started with Basic, upgraded to Premium/Family, and remained active.

Q10. Cliffhanger Comebacks
Detected users who returned to the same show within 1–7 days after an incomplete viewing session.

Tier 3 — Advanced SQL

Q11. Consecutive-Week Engagement
Identified users with viewing activity across four or more consecutive calendar weeks using the gaps-and-islands technique.

Q12. Churn Signal Detection
Identified users whose June watch time dropped by at least 50% compared with May, providing potential early churn signals.
