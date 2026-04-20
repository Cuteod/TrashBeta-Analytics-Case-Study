# TrashBeta Analytics Case Study  
## Turning Citizen Waste Complaints into Product Intelligence with Power BI

A data analytics case study on how survey insights were used to shape TrashBeta — a smart waste reporting platform for Nigerian communities.


## Project Overview

Waste management complaints in many urban communities are often fragmented across phone calls, WhatsApp chats, social media posts, and local government offices. This creates three major problems:

- No central reporting system  
- No visibility into recurring hotspots  
- No accountability after complaints are made  

To validate whether a digital solution could solve this, the team conducted a structured public survey and analyzed responses using **Power BI** before product design and engineering began.

This project became the analytical foundation for **TrashBeta** — a civic-tech waste reporting platform designed to improve reporting, transparency, and response coordination.

📖 Medium Article:  
🔗 https://medium.com/@cuteod/from-waste-complaints-to-product-strategy-how-data-analysis-shaped-trashbeta-b42a86fe2597 :contentReference[oaicite:0]{index=0}


## Business Problem

Citizens were reporting waste problems, but:

- Reports were scattered across channels  
- Issues remained unresolved for weeks or months  
- Service providers lacked structured operational data  
- Residents had low trust in existing systems  

The objective was to determine:

1. What waste issues occur most often?  
2. How severe are they?  
3. Which locations are most affected?  
4. Would citizens adopt a digital reporting tool?  
5. What features would drive trust and usage?


## Dataset Summary

| Metric | Value |
|---|---:|
| Total Responses | 301 |
| Collection Method | Google Form |
| Coverage | Multiple Nigerian States |
| Primary Market | Lagos |
| Analysis Tool | Power BI |
| Period | Dec 2025 – Jan 2026 |


## Tools Used

- **Power BI** – Dashboarding & KPI tracking  
- **Excel / CSV** – Data cleaning source file  
- **Google Forms** – Data collection  
- **Power Query** – Transformation  
- **DAX** – Measures & calculated metrics  


## Dashboard Structure

The report was divided into 3 analytical dashboards:

1. Problem Scope & Overview  
2. User Behaviour & Engagement  
3. Geographic Breakdown Analysis  


### Problem Scope & Overview

![](https://github.com/Cuteod/TrashBeta-Analytics-Case-Study/blob/main/Screenshot%202026-04-17%20210247.png)

#### Key KPIs

| KPI | Value |
|---|---:|
| Total Reports | 301 |
| Avg Urgency Score | 3.59 / 5 |
| High Urgency Reports | 59.8% |
| Chronic Issues | 50.8% |

#### Top Waste Problems

| Waste Type | Count | Share |
|---|---:|---:|
| Illegal Dumping Site | 128 | 42.5% |
| Overflowing Waste Bin | 71 | 23.6% |
| Blocked Drainage | 52 | 17.3% |
| Missed Collection | 45 | 15.0% |

Illegal dumping was the dominant issue, showing that many communities lack reliable or accessible legal disposal systems.


#### Duration of Problems

| Duration | Count |
|---|---:|
| 2–4 Weeks | 62 |
| Recurring | 57 |
| 1–3 Months | 55 |
| >3 Months | 41 |
| <24 Hours | 6 |


Only 6 issues were short-lived. Most waste complaints lasted weeks or months, indicating systemic response delays.


#### Main Community Impact

| Consequence | Count |
|---|---:|
| Bad Smell | 202 |
| Health Risk | 177 |
| Blocked Road / Drainage | 87 |
| Flood Risk | 79 |
| Safety Hazard | 74 |

#### Business Interpretation

Waste problems were strongly linked to health, mobility, and flooding — not just aesthetics.


### User Behaviour & Engagement

![](https://github.com/Cuteod/TrashBeta-Analytics-Case-Study/blob/main/Screenshot%202026-04-17%20210324.png)

#### Future App Adoption

| Response | Count | Share |
|---|---:|---:|
| Yes | 247 | 82.1% |
| Maybe | 50 | 16.6% |
| No | 4 | 1.3% |


Strong demand existed for a faster and more transparent reporting system.


#### Preferred Communication Channel

| Channel | Count |
|---|---:|
| Anonymous / No Update | 173 |
| SMS | 85 |
| WhatsApp | 84 |
| Email | 35 |
| Social Media | 27 |

Users preferred low-friction mobile communication over formal channels.

#### Recommended Feature Priorities:

- WhatsApp status alerts  
- SMS notifications  
- Anonymous reporting mode  


#### Engagement Funnel

| Stage | Count |
|---|---:|
| Reports Submitted | 301 |
| Contact Provided | 50 |
| Photo Willingness | 128 |
| App Ready | 247 |


There was high interest in the platform, but lower willingness to identify personally.

This indicated a **trust gap**.


### Geographic Breakdown Analysis

![](https://github.com/Cuteod/TrashBeta-Analytics-Case-Study/blob/main/Screenshot%202026-04-17%20210349.png)

#### Top States by Reports

| State | Reports |
|---|---:|
| Lagos | 222 |
| FCT | 14 |
| Ogun | 8 |
| Oyo | 8 |
| Osun | 8 |


Lagos represented **73.8%** of all responses, making it the strongest pilot market.


#### Lagos Signals

| Metric | Value |
|---|---:|
| Avg Urgency | 3.68 |
| Chronic Issues | 46.8% |
| App Interest | 87.4% |


Lagos had both high pain levels and high willingness to adopt a digital solution.

This is ideal for MVP rollout.

