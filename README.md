# Deloitte Australia Virtual Experience - Data Analytics & Forensic Technology

This repository contains the data analytics tasks completed during the Deloitte Australia Virtual Experience Program. The project focuses on data cleaning, transformation, logical mapping, and exploratory data analysis (EDA) using *Power BI* and *Power Query*.

## 📁 Project Structure
* Deloitte_forage_completion_certificate.pdf - Official program completion certificate.
* create equality class.png - Visual proof of the Power Query data transformation steps.
* results.png - Built intuitive Power BI Bar Charts to analyze the count of unhealthy machine across different factories and devices types.
* README.md - Project documentation and insights.

## 📊 Task 1: Machine Health & Exploratory Data Analysis (EDA)

*Objective:* Analyze factory machinery metrics to monitor unhealthy machine counts and predict maintenance triggers.

* *Metric Visualization:* Built dedicated Power BI dashboards using  Bar Charts to segregate Healthy vs Unhealthy machines.
* *Geographical Insights:* Mapped unhealthy machines against specific factory locations to identify operational bottlenecks and assist the engineering compliance team.

## 💻 Tech Stack Used
* *Tool:* Power BI Desktop
* *Engine:* Power Query (M Code)
* *Format:* Structured Data Transformation (ETL)

## 🛠️ Task 2: Forensic Technology & Data Transformation

*Objective:* Investigate organization-wide global factory metrics to analyze workplace diversity and equity data.

* *Data Cleansing:* Handled missing/null values within the continuous variables inside the dataset using Power Query.
* *Conditional Logic Mapping:* Implemented complex logical transformations using M Code to group the continuous equality metrics into clean categorical attributes:
  * Highly Discriminative (Scores $\le -20$ or $\ge 20$)
  * Unfair (Scores between $-10$ and $-19$, or $10$ and $19$)
  * Fair (Rest of the metrics)
* *Variance Analysis:* Utilized absolute variance to strictly analyze positive and negative deviations from the neutral equality benchmarks.
