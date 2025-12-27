Employee-Hourly-Efficiency-Dashboard
End-to-end analytics flow from data to action

This diagram shows how employee productivity and break data moves through the system:

SQL Server acts as the centralized data source

Cleaned and structured data is modeled in Power BI

KPIs and dashboards provide performance insights

Power Automate monitors compliance rules

Email alerts are sent automatically when violations occur

✅ Demonstrates full BI lifecycle design and automation thinking.

🗂️ Data Model (Star Schema) — Visual DescriptionStar Schema
## 🗂️ Data Model (Star Schema)

![Star Schema](assets/<img width="1920" height="1080" alt="Schema" src="https://github.com/user-attachments/assets/62df4831-759d-4df9-b023-3ad75a60be8a" />
)

Optimized data model for reporting performance and scalability

Fact tables store measurable activity like productivity and attendance

Dimension tables provide descriptive context (employee, date, team, process)

Star schema improves query speed and simplifies analysis

Supports drilldowns and cross-filtering in Power BI

✅ Reflects industry-standard dimensional modeling practices.

📊 Dashboard Overview — Visual Description

High-level performance monitoring dashboard for managers

KPI cards highlight productivity, efficiency, quality, SLA, and compliance

Visual trends show performance over time

Filters allow quick slicing by employee, team, or date

Designed for fast decision-making and visibility

✅ Focused on clarity, usability, and business value.

🔍 Employee-Level Drilldown — Visual Description

Detailed view for individual performance analysis

Employee-wise productivity and efficiency metrics

Break usage and compliance tracking

Quality and SLA indicators

Trend charts to identify performance patterns

✅ Enables targeted coaching and performance review.

🚨 Power Automate Flow — Visual Description

Automated break compliance monitoring workflow

Flow checks break duration against defined thresholds

Identifies policy violations automatically

Triggers an alert workflow when conditions are met

Reduces manual supervision effort

✅ Shows practical automation applied to real operations.

📧 Email Alert — Visual Description

Automated notification sent to managers

Includes employee name and violation details

Clearly states exceeded break limits

Enables quick corrective action

Improves compliance without manual tracking

✅ Demonstrates real-world alerting and governance automation.

🧠 KPI Logic Visual — Description

Simple and transparent KPI calculation logic

Productivity based on productive vs logged-in time

Efficiency compares actual vs expected output

Quality reflects error-free work rate

SLA tracks turnaround compliance

Break compliance flags violations automatically

✅ Designed to be understandable by both technical and non-technical users.
