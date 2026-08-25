# 📊-AM-Aggregator-CDL-Manager-Performance-Dashboard
This dashboard evaluates the performance of Aggregator Managers (AMs), also known as Channel Development Lead Managers (CDLs). It tracks their ability to grow and sustain qualified Points of Sale (POS), manage channel development, and earn performance-based bonuses.
 
### Table of Contents
1.	[Executive Summary](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#1-executive-summary)
2.	[Business Problem](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#2-business-problem)
3.	[Dataset Overview](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#3-dataset-overview)
4.	[Dashboard Workflow](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#4-dashboard-workflow)
5.	[Dashboard Visualization](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#5-dashboard-visualization)
6.	[Key KPIs](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#5-dashboard-visualization)
7.	[Insights](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#7-insights)
8.	[Recommendations](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#8-recommendations)
9.	[Technical Skills Demonstrated](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#9-technical-skills-demonstrated)
10.	[Project Outcome](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#10-project-outcome)
11.	[KPI Dashboard Summary](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard#11-kpi-dashboard-summary)

## 1. Executive Summary
The dashboard highlights Top 20 Performing AMs and Bottom 20 Performing AMs, providing management with actionable insights into qualification rates, net growth, and bonus distribution across regions.

## 2. Business Problem
Channel development requires consistent monitoring of POS qualification, retention, and growth. Without structured reporting, it is difficult to identify which managers are driving sustainable growth and which regions need intervention.

This dashboard solves that problem by providing real-time visibility into AM/CDL performance, enabling data-driven incentive decisions and targeted support.

## 3. Dataset Overview
| Metric                                | Description                               |
|---------------------------------------|-------------------------------------------|
| AM/CDL Code & Name                    | Identifies each Aggregator Manager        |
| Region / State                        | Operational geography                      |
| SM / RM Codes                         | Supervisory hierarchy                      |
| Qualified CDL (Current & Last Month)  | Measures new and retained qualified outlets|
| Qualification Rate                    | % of qualified POS vs total                |
| Net Increase                          | Growth in qualified POS this cycle         |
| Bonus Earned                          | Incentive tied to qualification            |
| Ranking                               | Position among peers                       |


## 4. Dashboard Workflow
  1.	Data Input: Aggregator/CDL performance data collected monthly.
  2.	Data Cleaning: Standardized codes, validated numeric fields, removed duplicates.
  3.	KPI Computation: Qualification rate, net increase, bonus, and ranking.
  4.	Visualization: Interactive dashboard with slicers by Regional Managers for      filtering.
  5.	Insights: Highlights top-performing AM/CDLs, regional strengths, and weak areas.

## 5. Dashboard Visualization
 ![](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard/blob/main/dashboard.png)

showing Top 20 vs Bottom 20 AMs, summary KPIs, and the slicer by Regional Managers.

This section visually demonstrates:
-	Summary KPIs (Qualified CDL this month, last month, count of CDL)
-	Top vs Bottom 20 AMs performance comparison
-	Regional Manager slicer for interactive filtering

## 6. Key KPIs
-	Qualification Rate (e.g., 0.81 → 81%)
-	Net Increase in Qualified CDL (e.g., +61 for top 20)
-	Bonus Earned (e.g., ₦288,400)
-	Ranking Position (e.g., 20th)
-	Retention (Rollover POS) (e.g., 20 retained outlets)
  
## 7. Insights
-	AM/CDLs with qualification rates above 0.75 consistently rank in the top 25.
-	Lagos and North Central regions show stronger qualification consistency.
-	Bonus earnings are directly tied to qualification rates and net growth.
-	Retention of CDL (rollover) is a key driver of sustainable performance.

## 8. Recommendations
-	Reward Consistency: Incentivize AM/CDLs maintaining qualification rates above 0.70.
-	Regional Support: Provide training in regions with qualification rates below 0.50.
-	Retention Focus: Encourage strategies that improve rollover CDL.
-	Automated Updates: Link dashboard to live data sources for real-time monitoring.
  
## 9. Technical Skills Demonstrated
-	Excel Dashboard Design
-	KPI Computation (Qualification Rate, Net Growth, Bonus)
-	Pivot Tables & Slicers
-	Conditional Formatting
-	Interactive Charting
-	Business Insight Generation
  
## 10. Project Outcome
The AM/CDL Performance Dashboard provides management with actionable insights into channel development. It highlights top performers, identifies weak regions, and supports incentive allocation, ultimately driving sustainable CDL growth and channel expansion.

## 11. KPI Dashboard Summary
| KPI Metric                   | Description                                               | Top 20 AMs | Bottom 20 AMs | Grand Total |
|-------------------------------|-----------------------------------------------------------|------------|---------------|-------------|
| Qualified CDL (This Month)    | Number of qualified CDLs managed by AMs in the current cycle | 109        | 83            | 192         |
| Qualified CDL (Last Month)    | Number of qualified CDLs managed by AMs in the previous cycle | 49         | 33            | 82          |
| Net Increase                  | Growth in qualified CDLs compared to last month           | +61        | +52           | +113        |
| Average Qualification Rate    | Ratio of qualified CDLs to total CDLs handled             | 0.78       | 0.54          | 0.66        |
| Bonus Earned (₦)              | Total incentive earned based on qualification performance | 288,400    | 154,000       | 442,400     |
| Ranking Range                 | Performance position among AMs                            | 1–20       | 21–40         | —           |


Dashboard Highlights
-	Top 20 AMs achieved a net increase of 61 qualified CDLs, showing strong growth momentum.
-	Bottom 20 AMs still recorded improvement (+52), indicating overall upward performance trends.
-The average qualification rate of 66% reflects moderate consistency across regions.
-	Regional slicers allow management to filter performance by RM, enabling targeted analysis.

 ![](https://github.com/victorhamvida-dotcom/-AM-Aggregator-CDL-Manager-Performance-Dashboard/blob/main/flowchart.png)
 
Data Collection → Cleaning → KPI Calculation → Dashboard Creation → Regional Filtering → Analysis → Insights → Management Decisions.
