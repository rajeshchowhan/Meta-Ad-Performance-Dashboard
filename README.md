# Meta Ads Performance Dashboard (Instagram + Facebook)

A Power BI project analyzing ad performance across the marketing funnel — from impressions to purchases — using a clean star-schema model and clearly defined KPIs.

## Project Overview

This dashboard breaks down how Meta ads perform across demographics, geographies, time patterns, and ad formats.
It highlights where the funnel leaks, which audiences respond best, and what optimizations actually matter.

## Data Model

### Star Schema:

Fact Table: ad_events

event_id, ad_id, user_id, timestamp, event_type, day_of_week, time_of_day

### Dimensions:

ads: ad_id, campaign_id, platform, ad_type, target_gender, target_age_group, interests

campaigns: campaign_id, name, dates, budget

users: user_gender, age, age_group, country, location, interests

## KPIs Tracked

Impressions

Clicks

Shares

Comments

Purchases

Engagements = Clicks + Shares + Comments

CTR, Engagement Rate, Conversion Rate, Purchase Rate

Total Budget & Avg Campaign Budget

## Dashboard Visuals

Donut chart — Target Gender performance

Bar chart — Age Group comparison

Map — Country-level distribution

Calendar heatmap — Monthly/Daily patterns

Stacked column — Weekly performance by ad type

Area chart — Hourly activity

Matrix — Platform × Ad Type metrics
## Key Insights

High engagement but poor conversion → major drop from clicks to purchases

Females aged 18–30 respond strongest

Video & Story ads outperform static formats

Peak engagement in afternoon & evening hours

Budget is not optimally aligned with top-performing segments

## Tech Used

Power BI (Modeling, DAX, Visualization)

Python, SQL, Excel (Recommended for ETL & validation)

## How to Use

Open Instagram Project.pbix in Power BI Desktop

Explore the interactive visuals & filters

Review insights + recommendations to understand ad performance gaps

## Dashboard Overview
![Meta Ad Performance Dashboard Page](https://github.com/rajeshchowhan/Meta-Ad-Performance-Dashboard/blob/533b811af671994a8b664b75e8eade30de638058/Meta%20Ad%20Dashboard.png)

