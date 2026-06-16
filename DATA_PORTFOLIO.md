# Data Quality Portfolio

This page is a short index of projects most relevant to Data Quality, Data Validation, Junior Data Analyst, Data Support, and SQL Support roles.

The focus is practical: messy data, missing values, duplicates, schema changes, suspicious records, row-level flags, repeatable checks, and clear reports.

## Positioning

I am transitioning into data-focused IT work. I am not presenting myself as a senior data engineer or senior developer.

My entry-level strength is careful validation: checking whether data is complete, consistent, explainable, and safe enough to use in reporting, migration, import/export, or business workflows.

## Core skills shown

- Data quality checks
- Duplicate detection
- Missing value checks
- Invalid format checks
- Basic SQL-style thinking: filters, groups, joins, NULLs, counts, mismatches
- CSV / Excel / Parquet / XML data review
- Row-level issue flags
- Clear actual vs expected notes
- Evidence-based reports
- Reproducible command-line workflows
- QA mindset applied to data

## Best projects to review first

### 1. Data Quality Audit CLI

Repository: `data-quality-audit-cli`

Reusable validation project for messy CSV and Parquet datasets. It uses rule-based checks and generates reviewable outputs such as summary reports, JSON metrics, HTML output, and flagged rows.

Why it matters:

- shows practical data validation logic
- focuses on exact affected rows, not vague summaries
- supports repeatable checks
- can be explained as a data quality gate before import, reporting, CRM usage, or business review

### 2. NYC Yellow Taxi Cleanup

Repository: `nyc-yellow-taxi-cleanup`

Multi-year data quality project using NYC taxi trip records. The important part is not only the data size, but the reasoning: keep suspicious records, flag them, compare years, and avoid deleting records without evidence.

Why it matters:

- shows record-level data quality flags
- handles schema drift between years
- separates anomalies from records that may still be valid
- explains why a data issue may come from source-system changes, not just dirty data

### 3. TED 2025 Data Quality Audit

Repository: `ted-2025-data-quality-audit`

Public procurement data quality audit focused on structured data extracted from XML packages. The project checks missing amounts, placeholder values, duplicate IDs, suspicious amounts, and consistency between reported totals.

Why it matters:

- shows data integrity checks on public-sector style data
- uses validation rules that map to real business risk
- produces reportable findings
- demonstrates careful treatment of missing and suspicious financial values

### 4. Customer Data Cleaning

Repository: `customer-data-cleaning`

Smaller practical project around messy customer-style data. Useful for showing basic cleanup and validation tasks closer to everyday business data work.

Why it matters:

- closer to common junior tasks
- easier to discuss in an interview
- connects directly to CSV/Excel cleanup, duplicates, missing fields, and formatting problems

## Secondary projects

QA/API repositories are secondary. They are still useful because many data roles involve checking imports, exports, APIs, reports, and system behavior. However, the main target is data quality and validation work, not pure manual testing.

## Target roles

- Junior Data Quality Analyst
- Data Validation Specialist
- Junior Data Analyst
- Data Support Specialist
- SQL Support Analyst
- Reporting Support Analyst
- Application Support Analyst with SQL/data checks
- QA/Data Quality Tester

## Honest scope

Current focus is entry-level data quality work: SQL basics, structured checks, practical validation, reproducible evidence, and careful reporting.

I do not claim senior-level Python, cloud, machine learning, data engineering, or production DBA expertise.
