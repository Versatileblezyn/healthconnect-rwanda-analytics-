# HealthConnect Rwanda - Data Analytics Project

## Project Overview

This project was completed as part of the AnalystLab Africa Experience Lab Internship, Cohort 23, in the Data Analytics track.

The project focuses on how HealthConnect Clinic in Rwanda can use data analytics and AI to reduce missed appointments and improve patient support.

The main objective is to transform healthcare data into meaningful business insights that can support better operational planning, financial monitoring, patient experience and decision-making.

## Business Problem

Healthcare organisations need reliable information to understand patient needs, monitor operations and make informed decisions.

HealthConnect aims to explore how data and AI can support:
- Better understanding of patient patterns.
- Improved appointment management.
- More effective operational planning.
- Financial monitoring.
- Improved patient experience and support.

## Tools and Technologies

- SQL – Data querying, transformation and validation.
- Microsoft Power BI – Data visualisation and dashboard development.
- GitHub – Project documentation and version control.

## Dashboard Development

The Power BI dashboard was organised into six analytical pages:

1. **Executive Dashboard:** High-level overview of key healthcare indicators.
2. **Patient Analytics:** Patient demographics and population patterns.
3. **Clinical Analytics:** Available clinical and diagnosis-related information.
4. **Financial Dashboard:** Revenue, billing and payment-related analysis.
5. **Operations Dashboard:** Operational indicators, facilities, beds and equipment records.
6. **Patient Experience:** Patient satisfaction ratings and feedback categories.

## Key Performance Indicators

The following figures were validated against the available project data:

| KPI | Result |
|---|---:|
| Registered Patients | 20,000 |
| Appointments | 5,000 |
| Doctors | 350 |
| Facilities | 20 |
| Average Patient Satisfaction | 2.99 |
| Revenue Summary Total | 1,132,677,500 |

*Note: The currency for the revenue figure was not specified in the available source data.*

## Key Business Insights

The analysis highlighted several areas requiring management attention:

- Patient demographics can support more targeted healthcare planning.
- Chronic condition patterns can inform service planning and patient support.
- Revenue trends require further investigation to understand changes over time.
- Billing and payment figures need careful interpretation because they represent different financial measures.
- Patient satisfaction and feedback provide useful signals for improving patient experience.
- Facility and equipment information requires better data labelling and reporting.

## Recommendations

Based on the available analysis, the following actions are recommended:

1. Strengthen patient experience monitoring and use feedback to identify improvement areas.
2. Investigate changes in monthly revenue alongside appointment and billing activity.
3. Use patient demographic and chronic condition patterns to support service planning.
4. Improve facility-level reporting by using clear facility names rather than relying only on IDs.
5. Improve the completeness and consistency of clinical and operational data.
6. Introduce reliable appointment outcome tracking to distinguish attended, missed, cancelled and rescheduled appointments.

## Data Limitations

The project identified important limitations that affect the interpretation of some findings:

- Facility names were not available in the supplied data.
- Detailed clinical transaction information, such as laboratory tests, prescriptions, admissions and referrals, was unavailable.
- The appointment CSV contained appointment identifiers, patient identifiers, doctor identifiers, facility identifiers, department identifiers, dates and visit types, but no attendance-status field.
- Therefore, a reliable no-show rate and attendance rate could not be calculated from that CSV.
- The bed-status chart showed 100% availability in the displayed records, but this should not be interpreted as confirmed hospital-wide capacity.
- Equipment records represented equipment counts, not equipment utilisation.
- Patient feedback data did not contain a clear date field.
- Revenue, billing and payment measures require further reconciliation before being treated as directly comparable.

## Testing and Validation

The analytical work included SQL-based checks of key figures, review of dashboard visuals, filter and slicer testing, and refinement of chart labels and readability.

Reported validation results included appointment count, doctor count, facility count, patient satisfaction and revenue totals.

Some limitations remain, including the absence of an appointment outcome field in the supplied appointment CSV.

## Project Integration and Collaboration

The Week 7 cross-track testing activity was not completed

## Project Deliverables

The project documentation is organised around the following deliverables:

- Final Analytics and Decision Support Report.
- Power BI dashboard.
- SQL analysis and validation evidence.
- KPI and financial testing records.
- Dashboard screenshots and evidence.
- Final project presentation.

## Project Structure

```text
healthconnect-rwanda-analytics/
│
├── README.md
│
├── dashboard/
│   └── HealthConnect_PowerBI_Dashboard.pbix
│
├── sql/
│   └── SQL_Analysis_and_Validation.sql
│
├── reports/
│   └── HealthConnect_Week8_Final_Analytics_Report.docx
│
├── evidence/
│   └── Week7_Testing_and_Validation/
│
└── presentation/
    └── HealthConnect_Week8_Final_Presentation.pptx
```

*The folder structure is a proposed organisation. Add only files that have actually been placed in the repository.*

## Conclusion

The HealthConnect Rwanda project demonstrates how data analytics can support healthcare decision-making by turning available data into understandable insights and practical recommendations.

It also highlights the importance of data quality, validation and transparent reporting. Reliable appointment outcome data, improved operational records and stronger financial reconciliation would help HealthConnect make more informed decisions in the future.

---

**Project:** HealthConnect Rwanda  
**Programme:** AnalystLab Africa Experience Lab Internship 
**Track:** Data Analytics  
**Author:** Osazuwa Ngozi Blessing
