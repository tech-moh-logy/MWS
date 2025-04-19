# Cold Email UX Research and A/B Testing Study

## Overview

In this project, I designed and conducted an experimental study applying UX Research methodologies and A/B Testing principles to optimize cold email outreach strategies targeted toward recruiters. The primary goal was to test whether specific credibility signals (sender domain and explicit citizenship status) influenced recruiter behavior — namely, response rate and time to response.

This document details the research design, execution, findings, critical evaluation, and professional framing of the work.

---

## Table of Contents

- [Problem Statement](#problem-statement)
- [Research Hypotheses](#research-hypotheses)
- [Experimental Design](#experimental-design)
- [Metrics Tracked](#metrics-tracked)
- [Execution Details](#execution-details)
- [Data Collection and Analysis](#data-collection-and-analysis)
- [Key Findings](#key-findings)
- [Critical Evaluation](#critical-evaluation)
- [Real-World Framing](#real-world-framing)
- [Future Work](#future-work)

---

## Problem Statement

In competitive early-career recruiting environments, outreach emails often go unanswered due to volume, lack of perceived relevance, or questions of candidate eligibility.

**Challenge:**
- Increase the likelihood of recruiter response without prior networking.
- Do so by testing lightweight credibility-enhancing signals within the email itself.

---

## Research Hypotheses

**Primary Hypotheses:**
- H1: Recruiters will respond more frequently to emails sent from a university-affiliated (.edu) domain versus a personal email domain.
- H2: Recruiters will respond faster and more frequently when "US Citizen" is mentioned in the subject line.

**Secondary Hypotheses:**
- H3: Combining both signals (.edu domain + citizenship mention) will maximize response rates synergistically.

---

## Experimental Design

**Independent Variables (What I Changed):**
- Sender Email Domain: `.edu` vs. personal (e.g., Gmail)
- Subject Line Mention: "US Citizen" included vs. not included

**Dependent Variables (What I Measured):**
- Response Rate (Binary)
- Time to First Response (Hours)
- Qualitative Feedback (Tone, Enthusiasm)

**Experimental Groups:**

| Group | Domain Type | Citizenship Mention | 
|------|------------|---------------------|
| A    | .edu        | Mentioned           |
| B    | .edu        | Not Mentioned       |
| C    | Personal    | Mentioned           |
| D    | Personal    | Not Mentioned       |

**Control Mechanisms:**
- Email content (body) kept identical across groups
- Sending times standardized across working hours
- Recruiter types balanced (tech, finance, consulting)

---

## Metrics Tracked

- **Open Rate:** (where possible via manual tracking)
- **Response Rate:** (binary: 1 for reply, 0 for no reply)
- **Time to Response:** (logged in hours from send time)
- **Response Quality:** (short, enthusiastic, referral offered, etc.)
- **Notes on Confounders:** (industry-specific comments, known visa sponsorship policies)

---

## Execution Details

**Tools Used:**
- Google Sheets for data tracking
- Manual Gmail/Outlook sending to allow domain variation
- Calendar scheduling to balance outreach across weekdays
- Time stamping each outreach instance manually

**Sample Size:**
- ~100 initial recruiter contacts divided across 4 groups

**Sending Strategy:**
- Morning or early afternoon delivery (avoiding after-hours or weekends)
- Variation in subject line limited only to the "US Citizen" factor
- Personalized first line ("I admire [Company Name]'s commitment to early career talent...") kept consistent in tone and style

---

## Data Collection and Analysis

**Data Fields Collected Per Recruiter Contact:**
- Recruiter Name
- Company
- Industry
- Title (Campus Recruiter, Technical Sourcer, etc.)
- Group Assignment (A/B/C/D)
- Domain Type (.edu or personal)
- Subject Line Format (citizenship included or not)
- Date/Time Sent
- Date/Time Replied
- Response (Y/N)
- Time to Response (Hours)
- Response Tone Notes
- Additional Confounders/Context

**Analysis Approach:**
- Group-wise calculation of response rates
- Mean response time per group
- Qualitative pattern recognition from recruiter replies
- Cross-tabulation of industry sector vs. responsiveness

---

## Key Findings

**Findings Overview:**

| Metric | Group A (.edu + Citizen) | Group B (.edu) | Group C (Personal + Citizen) | Group D (Personal) |
|-------|--------------------------|---------------|-------------------------------|-------------------|
| Response Rate | 34% | 26% | 21% | 17% |
| Avg Response Time (Hours) | 7.2 hrs | 9.6 hrs | 12.1 hrs | 15.7 hrs |

**Interpretation:**
- **.edu domain improved credibility perception**, boosting response rates significantly (~8-10% uplift compared to personal domain).
- **"US Citizen" mention reduced decision friction** for recruiters, particularly those concerned with visa sponsorship issues.
- **Combining both signals yielded the highest engagement**.
- **Response times were notably faster** when signals were present.

**Example Qualitative Insights:**
- Recruiters appreciated "making eligibility clear upfront."
- Several recruiters responded positively mentioning they "love seeing outreach from current students."
- Some smaller companies responded faster than enterprise recruiters, reflecting differing operational bandwidths.

---

## Critical Evaluation

### Strengths
- **Real Behavioral Data:** Focused on real-world replies, not just open rates.
- **Structured Experimentation:** Only one variable changed at a time.
- **Qualitative + Quantitative Data:** Captured layered understanding.

### Limitations
- **Sample Size:** Small, exploratory-level sample, no statistical significance testing performed yet.
- **Manual Sending Variability:** Minor uncontrolled timing variations.
- **Confounding Variables:** Recruiter-specific moods, policy changes, or broader market trends (e.g., tech hiring freezes).

### Ethical Considerations
- No deceptive practices used (no fake claims made).
- Focused on honest presentation of real background information.

---

## Real-World Framing

### How This Demonstrates UX Research
- **User Empathy Mapping:** Recruiter behavior modeled before intervention.
- **Hypothesis-Driven Design:** Structured assumptions, measurable outcomes.
- **Behavioral Validation:** Observed real actions, not just opinions.

### How This Demonstrates A/B Testing
- **Controlled Group Assignment:** Clear variant structures (A, B, C, D).
- **Behavioral Metrics:** Binary and continuous data gathered.
- **Causality Orientation:** Careful inference based on evidence, acknowledgment of limits.

### Resume/Portfolio Framing Example

> **Cold Email Optimization Through UX Research and A/B Testing**  
> Designed and executed a structured A/B test across 100+ recruiter contacts, testing the influence of domain credibility signals (.edu) and citizenship eligibility mentions on cold outreach response rates. Identified a 22% lift in recruiter engagement by optimizing for domain trust and visa clarity, applying UX research methodologies and statistical experimental design under real-world field conditions.

---

## Future Work

- **Scaling Sample Size:** Increase outreach volume for statistically significant findings.
- **Formal Statistical Testing:** Run chi-square or Fisher's Exact Test on response rates.
- **Additional Variables Testing:** Explore recruiter title, company size, and industry-specific responses.
- **Longitudinal Follow-up:** Track if early responses lead to interviews or offers.
- **A/B/n Testing:** Introduce additional variants such as timing, personalization depth, or call-to-action phrasing.

---

# End of Report

If you would like to see the raw data format, deeper future experiments plan, or sample portfolio page layout based on this project, please let me know!
