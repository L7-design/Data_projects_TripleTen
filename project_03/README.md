## Introduction
This project aim is to perform an analysis for the telecom operator Megaline. Megaline offers two prepaid plans, Surf and Ultimate. The goal is to examine which plan Surf or Ulimate brings in more revenue. This will support the company is readjusting there advertizing budget.

Purpose: 
The project aims to answer the following questions: 
1. Which plan surf or ultimate generates the most revenue?
2. Do users demographics (aka regions) impact revenue? 

## Data 
Description of the data: 

The user table (data on users): 
user_id — unique user identifier

first_name — user's name

last_name — user's last name

age — user's age (years)

reg_date — subscription date (dd, mm, yy)

churn_date — the date the user stopped using the service (if the value is missing, the calling plan was being used when this database was extracted)

city — user's city of residence

plan — calling plan name

The calls table (data on calls):
id — unique call identifier

call_date — call date

duration — call duration (in minutes)

user_id — the identifier of the user making the call

The messages table (data on texts):
id — unique text message identifier

message_date — text message date

user_id — the identifier of the user sending the text

The internet table (data on web sessions):

id — unique session identifier

mb_used — the volume of data spent during the session (in megabytes)

session_date — web session date

user_id — user identifier

The plans table (data on the plans):

plan_name — calling plan name

usd_monthly_fee — monthly charge in US dollars

minutes_included — monthly minute allowance

messages_included — monthly text allowance

mb_per_month_included — data volume allowance (in megabytes)

usd_per_minute — price per minute after exceeding the package limits (e.g., if the package includes 100 minutes, the 101st minute will be charged)

usd_per_message — price per text after exceeding the package limits

usd_per_gb — price per extra gigabyte of data after exceeding the package limits (1 GB = 1024 megabytes)

## Libraries Used 
Pandas, Numpy, Matplotlib, Seaborn, Scipy  

## Table of Contents 
1. Introduction
2. Data exploration and preprocessing of data
3. Data Aggregation
4. Examining User Behavior
5. Hypothesis Testing
6. Conclusion  
