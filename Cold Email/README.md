# Cold Email A/B Testing for Internship Applications

## Context

In my internship search, I wanted to experiment with the factors that might influence cold email response rates. Specifically, I tested the impact of email domains (college-affiliated, personal, and general-use) and the inclusion of "US Citizen" in the subject line on recruiter engagement. This experiment was designed to provide insights into how these elements affect response rates and response time.

## Objective

The aim was to determine which combination of **email domain** and **subject line** results in the highest likelihood of getting a reply from recruiters. I hypothesized that a college-affiliated domain and a well-defined subject line might improve engagement.

## Hypotheses and Rationale

- **.edu Domain Hypothesis**: I expected that using a college-affiliated `.edu` domain would improve credibility and legitimacy in the eyes of recruiters, increasing the likelihood of responses. Recruiters might associate `.edu` addresses with currently enrolled students and trust that outreach is genuine.
- **"US Citizen" Subject Line Hypothesis**: Including "US Citizen" was hypothesized to speed up recruiter decision-making by immediately addressing a common qualification requirement, thus possibly improving response rates and reducing response time.

## Experiment Design

### Variables Tested

1. **Email Domain**:
   - `.edu` (college-affiliated domain)
   - `@gmail.com` (personal email)
   - `@outlook.com` (general-use email)

2. **Subject Line**:
   - **With "US Citizen"**
   - **Without "US Citizen"**

### Email Content

- **Body**: The body of the email remained consistent across all emails. It included:
  - A brief personal introduction
  - Relevant skills (technical and soft skills)
  - Target internship roles (e.g., Software Engineering Intern, AI/ML Intern)
  - A concise call to action asking for a referral or information about available internships
- **Tone**: Professional and polite, while remaining approachable.
- **Attachments**: No resume or additional files were attached to avoid spam filters.

### Recruiter Targeting

- **Industries**: Mainly Technology, Finance, and Consulting.
- **Company Size**: Targeted mid-sized firms (200–2000 employees) and high-growth startups.
- **Role Focus**: Recruiters who specifically mentioned internship or new grad opportunities in their LinkedIn title or job postings.

### Sample Size and Sending Volume

- Approximately **35–50 cold emails** were sent per domain group.
- Both subject line variations were tested simultaneously within each domain group.

### Timing Consistency

- Emails were sent between **Tuesday and Thursday**, between **9:00 AM and 12:00 PM EST**, based on research suggesting recruiters are more responsive during these windows.

### Tools Used

- **Google Sheets** for tracking outreach and responses.
- **Gmail** for sending emails manually to avoid spam flags.
- **Mailtrack** (free version) to confirm when emails were opened.
- **Filters** in Gmail to organize and monitor responses.

## Data Structure (Excel-Like Format)

| Recruiter Industry | Company Size | Email Domain | Subject Line Variant | Day Sent | Time Sent | Response (Y/N) | Time-to-Response (Hours) |
|---------------------|--------------|--------------|----------------------|----------|-----------|----------------|---------------------------|
| Technology          | 500          | .edu         | With US Citizen       | Tuesday  | 9:30 AM   | Yes            | 12                        |
| Finance             | 1200         | .edu         | No US Citizen         | Wednesday| 10:15 AM  | Yes            | 19                        |
| Consulting          | 300          | @gmail.com   | With US Citizen       | Thursday | 11:00 AM  | No             | -                         |
| Technology          | 1500         | @outlook.com | No US Citizen         | Tuesday  | 9:45 AM   | No             | -                         |
| Finance             | 700          | @gmail.com   | With US Citizen       | Wednesday| 10:45 AM  | Yes            | 20                        |
| Technology          | 400          | .edu         | With US Citizen       | Thursday | 9:00 AM   | Yes            | 14                        |

*(Sample rows above; full data tracked similarly)*

---

## Results Summary

| Email Domain   | Subject Line: "US Citizen" | Reply Rate (%) | Avg. Time-to-Response (Hours) |
|----------------|----------------------------|----------------|-------------------------------|
| .edu           | Yes                        | 26%            | 15 hours                      |
| .edu           | No                         | 24%            | 17 hours                      |
| @gmail.com     | Yes                        | 16%            | 22 hours                      |
| @gmail.com     | No                         | 14%            | 24 hours                      |
| @outlook.com   | Yes                        | 13%            | 25 hours                      |
| @outlook.com   | No                         | 11%            | 27 hours                      |

---

## Insights

### Impact of Domain

- `.edu` domains consistently outperformed others in both reply rates and response speed.
- Recruiters might perceive `.edu` addresses as signals of legitimacy, current enrollment, and readiness for internships.
- `@gmail.com` performed reasonably well but was still behind `.edu`.
- `@outlook.com` had the lowest engagement, possibly due to lower association with professional or academic credibility.

### Impact of Subject Line

- Including "US Citizen" improved reply rates slightly across all domains.
- The effect was strongest for `.edu` addresses.
- Time-to-response also slightly decreased when "US Citizen" was included, suggesting recruiters might prioritize easy-to-qualify candidates.

---

## Further Analysis

### Statistical Significance

- Due to the small sample size (~35–50 emails per variation), results are indicative but not statistically significant.
- Larger-scale testing would be necessary to establish robust conclusions.

### Cost-Benefit Reflection

- **Time Invested**: ~10 hours across several weeks preparing emails, targeting recruiters, and tracking responses.
- **Benefits**:
  - Multiple interview opportunities gained directly from cold emails.
  - Improved cold email templates and personalization strategies.
  - Greater understanding of recruiter behavior.

### Unexpected Findings

- Some recruiters responded even without "US Citizen" in the subject line, emphasizing that email content clarity and relevance also play crucial roles.
- A few responses came much later (2–5 days after sending), indicating that initial non-responses do not always imply rejection.

### Limitations

- Sample pool limited mainly to tech, finance, and consulting industries.
- Mostly focused on mid-sized companies; not enough large enterprise or very small startup samples.
- Timing bias: Sending during business hours only; no weekend or late-night testing.
- No follow-up emails were sent, which could have influenced final reply rates.

---

## Future Directions and Application

### Next Steps

- Test personalization levels (e.g., mentioning specific company initiatives or recruiter posts).
- Experiment with different subject line styles (e.g., "Internship Inquiry - Software Engineer" vs. "Seeking Internship - US Citizen - AI/ML").
- Include controlled follow-up sequences to measure second-attempt effectiveness.
- Analyze responses by recruiter seniority (e.g., senior recruiter vs. junior recruiter).

### Broader Implications

- Findings suggest that **signal quality** (e.g., domain, keywords like "US Citizen") matters significantly in outreach.
- Strategic structuring of cold emails can boost visibility and response even without prior connections.

### Impact on My Job Search

- Based on these insights, I have prioritized using my `.edu` email for cold outreach whenever possible.
- I also incorporate important eligibility information in the subject or first line of my emails when relevant.
- These changes have contributed directly to a higher number of positive recruiter responses and interview invitations during my internship search.

---

# Summary

This project highlights my ability to:
- Conduct real-world A/B testing with controlled variables.
- Apply user behavior analysis techniques outside a purely technical environment.
- Optimize communication strategies based on data-driven insights.
- Reflect critically on results, acknowledge limitations, and plan for continuous improvement.
