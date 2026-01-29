# Change of Shift (COS) Penalty Audit – Power BI

This project demonstrates a payroll audit dashboard built in Power BI
to identify Change of Shift (COS) penalty compliance issues.

![COS Audit Dashboard](images/cos_audit_dashboard.png)

## Problem Statement
COS penalties are expected when an employee’s shift start time
changes by 4 or more hours between consecutive working days.
In practice, payroll systems may miss or incorrectly apply these penalties.

## Audit Approach
- COS rows are treated as payments, not shifts
- Shift timing logic uses only ORD and LEAVE records
- Daily shifts are consolidated per employee per day
- Expected COS is calculated independently
- Actual COS payments are checked at the final audit stage

This separation prevents false triggers and ensures audit accuracy.

## Dashboard Highlights
- Overall COS compliance KPIs
- Missing vs Incorrect COS penalties
- Employee-level drilldown analysis

## Data Notice
⚠️ No real payroll or employee data is included.
The Power BI file contains no embedded dataset and is shared
for portfolio and demonstration purposes only.
