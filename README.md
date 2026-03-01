# SQL-Project-Hospital-Operations-Analysis
Analyzed hospital operations using SQL joins and aggregations to evaluate doctor utilization, appointment status trends, departmental revenue, and revenue at risk from pending payments.

# Dataset Structure
relational database consists of 4 tables
doctors – Doctor details and department information
patients – Patient records
appointments – Appointment scheduling and status tracking
billing – Revenue and payment status information
Foreign key relationships were implemented to simulate real hospital operations data flow.

# SQL Concepts Used
Multi-table JOINs
GROUP BY & ORDER BY
Conditional aggregation using CASE
Percentage calculations
Revenue leakage analysis
Ratio-based KPI computation

# Key KPIs Computed
Doctor Utilization % = Completed Appointments / Total Appointments
Cancellation Rate by Department
Revenue by Department
Revenue at Risk (Pending Payments)
Appointment Status Distribution

# Key Insights
Certain departments showed lower utilization rates, indicating capacity inefficiency.
Cancellation and no-show rates contributed to measurable operational loss.
Revenue was concentrated in specific departments.
Pending payments created short-term cash flow risk.
Some doctors had significantly lower completion rates compared to peers.

# Business Recommendations
Implement automated appointment reminders to reduce no-shows.
Introduce partial advance payment for high-value consultations.
Monitor department-level cancellation patterns regularly.
Track doctor utilization metrics for performance optimization.
