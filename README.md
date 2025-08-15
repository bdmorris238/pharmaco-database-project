# PharmaCorp Database & Data Warehouse Project

## Overview
This project builds a **transactional relational database** and a **data warehouse** for PharmaCorp, enabling:
- Market share and profit analysis.
- Treatment effectiveness evaluation.
- Secure, role-based patient record access.

The work includes SQL scripts for database creation, queries, fact tables, and stored procedures, plus a final business analysis presentation.

---

## Files
- `sql/` – Contains SQL scripts for:
  1. Creating transactional database schema.
  2. Analytical queries.
  3. Data warehouse creation.
  4. Fact table generation.
  5. Stored procedure / server setup code.
- `reports/final-presentation.pdf` – Business context, findings, dashboards, and AWS/Snowflake architecture.

---

## Tech Stack
- **SQL** (PostgreSQL syntax)
- **AWS**: RDS, S3, CloudWatch, IAM, Glue, Kinesis
- **Snowflake** for analytics
- Relational vs. NoSQL comparison

---

## Key Insights
- **Acquisition Decision**: MediHealth acquisition raised market share from 12.7% to over 29% and profits from ~$5,243 to ~$11,975.
- **Cost-Effectiveness Analysis**: COVID-19 treatment identified as least cost-effective; intensity level rose from 7 to 9 in 2023.
- **Security**: Implemented role-based access (Doctor, Patient) with row-level security.

---

## How to Use
1. Clone repo:
   ```bash
   git clone https://github.com/bdmorris238/pharmaco-database-project.git
