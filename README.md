# Marketing Campaign Analysis

## 1. Business Case Study

Novacart runs marketing campaigns across multiple channels, including Google, Facebook, Instagram, Email, Influencer, and YouTube. The company collects information about campaign spending, customer responses, conversions and revenue. However, having marketing data alone does not guarantee that the company knows where its marketing investment is producing the best results.

The purpose of this project is to analyze Novacart's marketing performance from a business perspective and identify opportunities to improve campaign effectiveness, customer targeting, channel selection and marketing investment. The analysis focuses on converting historical marketing and customer behavior into clear business recommendations.

The overall goal is to help Novacart answer a simple but important question:

> **Where should the company focus its marketing efforts to achieve better results?**

---

# 2. Problem Statement

Novacart is investing in multiple campaigns and marketing channels, but campaign performance is not consistent. Some campaigns generate significantly better returns than others, while some customer groups respond differently to different marketing channels.

The company therefore needs a better understanding of which campaigns are generating strong returns, which campaigns need improvement, which customer groups are most valuable, which channels work best for different customer segments, and whether the current marketing investment is aligned with performance.

### Core Business Problem

> **Novacart needs to identify the right campaign, the right customer, the right marketing channel, and the right level of investment to improve marketing effectiveness and reduce inefficient marketing spending.**

This project addresses the problem by analyzing campaign performance, customer behavior, channel effectiveness and budget allocation together rather than looking at each area separately.

---

# 3. Technology Used

## Technologies Used

| Technology | Purpose |
|---|---|
| **MySQL Workbench** | Used to store, clean, validate and prepare marketing data. |
| **SQL** | Used to calculate marketing metrics and prepare the analytical dataset. |
| **Python** | Used to perform exploratory analysis and identify business patterns. |
| **Pandas** | Used for data manipulation and analysis. |
| **NumPy** | Used for numerical calculations. |
| **Matplotlib** | Used to visualize analytical results. |
| **Seaborn** | Used to understand distributions and relationships. |
| **Power BI** | Used to present business insights and recommendations through an interactive dashboard. |

The technologies were selected based on the role they play in the overall business-analysis process. The database and SQL layer provided a reliable foundation for the data, Python helped investigate customer and marketing behavior, and Power BI converted the findings into a form that business stakeholders can easily understand.

# 4. Problems Identified from the Analysis

The analysis identified several important marketing problems within Novacart's business.

## Problem 1 — Campaign Performance is Uneven

Different campaigns generate significantly different returns.

For example:

- Monsoon Collection → **94.49 ROAS**
- Winter Collection → **52.39 ROAS**

This indicates that Novacart should not distribute marketing investment equally across campaigns. Strong campaigns have demonstrated better returns, while weaker campaigns require investigation before additional investment.

---

## Problem 2 — Marketing Channels Have Different Performance

The analysis showed that marketing channels generate different levels of return.

| Channel | ROAS |
|---|---:|
| Google | **86.06** |
| Facebook | **80.67** |
| Email | **79.69** |
| Instagram | 70.62 |
| Influencer | 63.79 |
| YouTube | 62.59 |

Google produces the strongest overall return, while YouTube and Influencer have comparatively lower returns in the analyzed data.

This means Novacart should evaluate channels based on their actual contribution rather than assuming that every channel is equally effective.

---

## Problem 3 — Customer Groups Have Different Needs

The analysis identified four major customer groups:

- Potential
- Discount Seeker
- At Risk
- High Value

These customers have different behaviors and business value.

For example, a High Value customer should be treated differently from a Discount Seeker because their relationship with the company and purchasing behavior are different.

Therefore, a single marketing strategy for all customers may not be effective.

---

## Problem 4 — Channel Effectiveness Depends on Customer Segment

The analysis found that the strongest acquisition channel varies by customer segment.

| Customer Segment | Best Channel | Conversion Rate |
|---|---|---:|
| Discount Seeker | Facebook | **14.62%** |
| High Value | Facebook | **13.88%** |
| At Risk | Facebook | **13.85%** |
| Potential | Google | **12.67%** |

This means there is an opportunity to make marketing more targeted.

Instead of asking:

> "Which is the best channel?"

Novacart should ask:

> **"Which channel is best for this particular type of customer?"**

---

## Problem 5 — Opportunity to Optimize Marketing Budget

The performance-weighted analysis showed differences between the current budget allocation and the recommended allocation scenario.

| Channel | Current Share | Recommended Share |
|---|---:|---:|
| Google | 26.63% | **31.58%** |
| Facebook | 15.53% | **23.67%** |
| Email | 9.33% | **23.29%** |
| Instagram | 22.99% | **9.74%** |
| Influencer | 4.61% | **7.03%** |
| YouTube | 20.91% | **4.68%** |

The analysis suggests that some channels may deserve additional investment, while others should be reviewed or optimized.

These numbers should be treated as **performance-based scenarios**, not as guaranteed optimal budget allocations.

---

# 5. Business Questions and Their Answers

## Q1. Which campaigns generate the highest and lowest ROAS?

### Answer

**Monsoon Collection** generated the highest ROAS at **94.49**, while **Winter Collection** generated the lowest at **52.39**.

This shows a clear performance difference between campaigns. Novacart should prioritize campaigns that consistently generate stronger returns and investigate the reasons behind weak campaign performance before increasing their investment.

---

## Q2. Which campaigns need creative, conversion or strategy optimization?

### Answer

**Winter Collection** requires particular attention because of its low ROAS and relatively weak conversion performance.

When a campaign has low engagement, Novacart should review the advertisement creative, messaging and audience targeting. When customers engage but do not convert, the company should investigate the offer, landing page, pricing and customer experience.

The key finding is that Novacart should identify the reason for poor performance before simply increasing or decreasing the campaign budget.

---

## Q3. Which channels generate the strongest returns?

### Answer

**Google** generated the strongest overall return with a ROAS of **86.06**, followed by **Facebook at 80.67** and **Email at 79.69**.

This indicates that these channels deserve greater attention when planning future marketing activity. However, channel performance should continue to be monitored because historical performance does not guarantee future performance.

---

## Q4. Which customer segment contributes the most customers and revenue?

### Answer

**Potential** is the largest customer segment with **1,011 customers** and approximately **₹25.21M in revenue**.

This makes Potential customers an important growth opportunity for Novacart. Rather than treating them simply as existing customers, the company can focus on converting them into more frequent and higher-value customers.

---

## Q5. Which acquisition channel works best for each customer segment?

### Answer

The analysis identified the following strongest combinations:

| Customer Segment | Best Channel | Conversion Rate |
|---|---|---:|
| Potential | **Google** | **12.67%** |
| Discount Seeker | **Facebook** | **14.62%** |
| High Value | **Facebook** | **13.88%** |
| At Risk | **Facebook** | **13.85%** |

The key business insight is that there is no single best channel for every customer group.

Novacart can improve targeting by matching customer segments with the channels where they demonstrate stronger conversion behavior.

---

## Q6. Which channels appear under- or over-allocated?

### Answer

The performance-weighted framework suggests greater allocation potential toward:

- Google
- Facebook
- Email
- Influencer

It suggests reviewing:

- Instagram
- YouTube

The purpose is not to immediately move the entire budget. Instead, Novacart should test changes on a smaller scale and measure whether the expected improvement actually occurs.

---

## Q7. Which campaigns should be scaled or maintained?

### Answer

Strong campaign candidates include:

- Monsoon Collection
- Flash Sale
- Summer Sale
- VIP Customer Offer

These campaigns demonstrated strong performance in the analysis.

Weaker campaigns should first be investigated and optimized before receiving additional investment.

The business principle is:

> **Scale what works, fix what does not, and continuously monitor the results.**

---

## Q8. Which customer groups require retention, re-engagement or promotional strategies?

### Answer

| Customer Group | Recommended Strategy |
|---|---|
| **Potential** | Personalized nurturing and conversion |
| **Discount Seeker** | Discounts and promotions |
| **At Risk** | Re-engagement and win-back |
| **High Value** | VIP retention and premium offers |

Each segment requires a different marketing approach.

This allows Novacart to move from a general marketing strategy toward a more customer-specific approach.

---

# 6. Recommendations to Solve the Problems

## Recommendation 1 — Scale High-Performing Campaigns

Novacart should prioritize campaigns that demonstrate strong returns, such as Monsoon Collection, Flash Sale, Summer Sale and VIP Customer Offer.

However, scaling should be gradual and performance should be monitored after additional investment.

The objective is to increase investment where there is evidence of strong performance rather than simply increasing the budget for every campaign.

---

## Recommendation 2 — Optimize Weak Campaigns Before Increasing Investment

For weaker campaigns such as Winter Collection, Novacart should first identify the cause of poor performance.

The company should review:

- Advertisement creative
- Audience targeting
- Offer attractiveness
- Pricing
- Landing-page experience
- Conversion process

Only after identifying and correcting the problem should additional investment be considered.

---

## Recommendation 3 — Use Customer-Specific Marketing

Novacart should not use the same strategy for every customer.

### Potential

Focus on:

> Personalized offers, relevant recommendations and conversion campaigns.

### Discount Seeker

Focus on:

> Discounts, promotions, flash sales and limited-time offers.

### At Risk

Focus on:

> Re-engagement, reminders and win-back campaigns.

### High Value

Focus on:

> VIP treatment, loyalty benefits, premium offers and retention.

---

## Recommendation 4 — Match Channels to Customer Segments

The analysis supports the following channel strategy:

```text
Potential
    ↓
Google

Discount Seeker
    ↓
Facebook

High Value
    ↓
Facebook

At Risk
    ↓
Facebook
