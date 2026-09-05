India Human Voice Agent Prospects --- Data Analytics & Power BI Dashboard

Project Overview

This project analyzes a prospect database of 203 unique companies in
India relevant to human voice-agent solutions.

The goal was to transform prospect data into a structured, validated and
decision-oriented dataset that supports data enrichment, business
development and outreach prioritization.

The project combines Python/Pandas for data cleaning and validation
with Power BI for interactive business intelligence and
visualization.

Business Objectives

Clean and standardize the prospect database.

Standardize inconsistent industry classifications.

Validate email, phone and website information.

Measure database completeness and data gaps.

Score prospects based on outreach readiness.

Prioritize companies for business-development outreach.

Build an interactive Power BI dashboard.

Tools & Technologies

Python

Pandas

NumPy

Regular Expressions

Jupyter Notebook / VS Code

Microsoft Power BI

DAX

Microsoft Excel

Project Workflow

Raw Prospect Data
       ↓
Data Cleaning & Standardization
       ↓
Missing-Value Treatment
       ↓
Industry Classification
       ↓
Email / Phone / Website Validation
       ↓
Data Completeness Scoring
       ↓
Outreach Scoring & Prioritization
       ↓
Power BI Dashboard
       ↓
Business Insights & Recommendations

Data Cleaning & Transformation

Column Standardization

The source fields were standardized into analytical fields such as
Company, Industry, Leadership, CEO Email, Current Email, Phone and
Website.

Missing-Value Treatment

Blank cells and placeholder values such as Not Found, N/A, None
and Contact form only were treated as missing values.

Industry Standardization

Raw industry descriptions were mapped into consistent Industry_Main
categories, including:

Technology

Financial Services

Healthcare

Education

Automotive & Mobility

Real Estate

Recruitment & HR

Logistics & Supply Chain

E-commerce & Retail

Marketing

Home Services

Travel & Hospitality

Energy & CleanTech

Email Validation

Email values were cleaned, normalized and checked using regular
expressions. Availability and email-type fields were created to
distinguish leadership, business, generic and missing email records.

Phone Validation

Phone values were normalized and validated using a stricter Indian
mobile-number rule. This produced Phone_Clean, Phone_Valid,
Phone_Available and missing-phone indicators.

Website Validation

Website values were normalized and checked for a basic valid URL
pattern.

Data Quality Framework

A weighted Data Completeness Score was created for each company.

Field           Weight

Email               30
Phone               20
Leadership          20
Website             20
Industry            10
Total      100

Quality Categories

Score      Category

80--100    High
50--79     Medium
Below 50   Low

Outreach Prioritization

An Outreach Score was created to measure practical contactability.

Field           Weight

Email               40
Phone               25
Leadership          20
Website             15
Total      100

Outreach Priority

Score      Priority

80+        High Priority
50--79     Medium Priority
Below 50   Low Priority

Prospects are also classified as:

Email + Phone

Email Only

Phone Only

No Direct Contact

Power BI Dashboard

The final dashboard provides an interactive view of prospect volume,
data quality, industry distribution and outreach readiness.

Main KPIs

Total Companies: 203

Email Coverage: 83.7%

Phone Coverage: 39.4%

Website Coverage: 95.1%

Overall Completeness: 77.0%

Missing Emails: 33

Missing Websites: 10

Missing Phone Numbers: 123

Dashboard Visuals

Companies by Industry --- shows the distribution of prospects across
standardized industries.

Email Coverage by Industry --- compares email availability between
industries and identifies enrichment opportunities.

Outreach Priority --- shows 75 High Priority, 99 Medium Priority and
29 Low Priority companies.

Industry × Outreach Priority --- combines industry size and outreach
priority to identify where the strongest prospect opportunities are
concentrated.

Overall Completeness --- provides a single view of average
availability across email, phone, website and leadership information.

Key Business Insights

Phone data is the largest enrichment gap. Phone coverage is only
39.4%, leaving 123 companies without a validated phone number.

Email coverage is relatively strong. 83.7% of companies have
usable email coverage, while 33 require email enrichment.

Website coverage is strong. 95.1% of companies have a usable
website.

The prospect base is concentrated in major industries.
Technology, Financial Services, Healthcare, Education and Automotive
& Mobility are among the largest groups.

Marketing requires attention. Email coverage is approximately
40%, making it the clearest industry-level email enrichment
priority.

The outreach pool is actionable. 75 companies are High Priority
and 99 are Medium Priority.

Recommended Business Actions

Prioritize phone enrichment for the 123 records without validated
phone numbers.

Enrich the 33 records without usable email information.

Start outreach with the 75 High Priority prospects.

Use Industry_Main to create industry-specific campaigns.

Review Medium Priority companies and enrich missing fields to move
suitable records into the High Priority pool.

Apply the same validation and scoring rules when new prospects are
added.

Dashboard Preview

Place the final screenshot in:

screenshots/dashboard.png

Then add:

![Power BI Dashboard](screenshots/dashboard.png)

Repository Structure

India-Human-Voice-Agent-Prospects/
│
├── README.md
├── python/
│   └── data_cleaning.py
├── powerbi/
│   └── India_Human_Voice_Agent_Prospects.pbix
├── documentation/
│   └── India_Human_Voice_Agent_Prospects_Dashboard_Report.pdf
├── screenshots/
│   └── dashboard.png
└── data/
    └── Cleaned_203_Companies.xlsx

Privacy note: Do not publish real personal email addresses or
phone numbers in a public GitHub repository. Use an anonymized/sample
dataset or exclude identifiable prospect data.

Documentation

The documentation folder contains the detailed PDF report covering the
methodology, data cleaning, validation, scoring logic, dashboard
visuals, insights and recommended actions.

Project Outcome

This project demonstrates an end-to-end Business Analytics workflow:

Data → Cleaning → Validation → Scoring → Visualization → Business
Decision

The final dashboard helps answer:

What data is missing?

Which industries need enrichment?

How complete is the prospect database?

Which prospects are most actionable?

Where should outreach and enrichment efforts be focused?

Author

Yug Borda

Business Analyst | Data Analytics | Power BI | SQL | Python
