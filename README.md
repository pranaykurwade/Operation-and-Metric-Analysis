# Operation-and-Metric-Analysis

# Problem Statement:
Operational Analytics is a crucial process that involves analyzing a company's end-to-end operations. This analysis helps identify areas for improvement within the company. As a Data Analyst, you'll work closely with various teams, such as operations, support, and marketing, helping them derive valuable insights from the data they collect.

One of the key aspects of Operational Analytics is investigating metric spikes. This involves understanding and explaining sudden changes in key metrics, such as a dip in daily user engagement or a drop in sales. As a Data Analyst, you'll need to answer these questions daily, making it crucial to understand how to investigate these metric spikes.

In this project, you'll take on the role of a Lead Data Analyst at a company like Microsoft. You'll be provided with various datasets and tables, and your task will be to derive insights from this data to answer questions posed by different departments within the company. Your goal is to use your advanced SQL skills to analyze the data and provide valuable insights that can help improve the company's operations and understand sudden changes in key metrics.

# Case Study 1: Job Data Analysis
You will be working with a table named job_data with the following columns:

<br>job_id: Unique identifier of jobs
<br>actor_id: Unique identifier of actor
<br>event: The type of event (decision/skip/transfer).
<br>language: The Language of the content
<br>time_spent: Time spent to review the job in seconds.
<br>org: The Organization of the actor
<br>ds: The date in the format yyyy/mm/dd (stored as text).<br>

# Tasks:

# Jobs Reviewed Over Time:
<br>Objective: Calculate the number of jobs reviewed per hour for each day in November 2020.<br>
<br>Your Task: Write an SQL query to calculate the number of jobs reviewed per hour for each day in November 2020.<br>
# Throughput Analysis:
<br>Objective: Calculate the 7-day rolling average of throughput (number of events per second).<br>
<br>Your Task: Write an SQL query to calculate the 7-day rolling average of throughput. Additionally, explain whether you prefer using the daily metric or the 7-day rolling average for throughput, and why.<br>
# Language Share Analysis:
<br>Objective: Calculate the percentage share of each language in the last 30 days.<br>
<br>Your Task: Write an SQL query to calculate the percentage share of each language over the last 30 days.<br>
# Duplicate Rows Detection:
<br>Objective: Identify duplicate rows in the data.<br>
<br>Your Task: Write an SQL query to display duplicate rows from the job_data table.<br>

# Case Study 2: Investigating Metric Spike
You will be working with three tables:

users: Contains one row per user, with descriptive information about that user’s account.
events: Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).
email_events: Contains events specific to the sending of emails.

# Tasks:

# Weekly User Engagement:
<br>Objective: Measure the activeness of users on a weekly basis.<br>
<br>Your Task: Write an SQL query to calculate the weekly user engagement.<br>
# User Growth Analysis:
<br>Objective: Analyze the growth of users over time for a product.<br>
<br>Your Task: Write an SQL query to calculate the user growth for the product.<br>
# Weekly Retention Analysis:
<br>Objective: Analyze the retention of users on a weekly basis after signing up for a product.<br>
<br>Your Task: Write an SQL query to calculate the weekly retention of users based on their sign-up cohort.<br>
# Weekly Engagement Per Device:
<br>Objective: Measure the activeness of users on a weekly basis per device.<br>
<br>Your Task: Write an SQL query to calculate the weekly engagement per device.<br>
# Email Engagement Analysis:
<br>Objective: Analyze how users are engaging with the email service.<br>
<br>Your Task: Write an SQL query to calculate the email engagement metrics.<br>
