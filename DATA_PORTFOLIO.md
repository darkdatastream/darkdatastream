# Data Quality Portfolio

This page is a short index of projects most relevant to Data Quality Analyst, Data Validation Specialist, and Data Support roles.

The focus is practical: messy data, missing values, duplicates, schema changes, suspicious records, row-level flags, repeatable checks, and clear reports.

## Positioning

I am transitioning into data-focused IT work. I am not presenting myself as a senior data engineer. 

My entry-level strength is rigorous validation: checking whether data is complete, consistent, explainable, and safe enough to use in reporting, migration, or business workflows.

## Core skills shown

- Data quality checks & Row-level issue flags
- Duplicate & Missing value detection
- Schema validation & Invalid format checks
- SQL querying: filters, aggregations, JOINs, NULL handling, mismatches
- High-performance data processing (CSV / Parquet / XML)
- Clear actual vs expected notes & Evidence-based reports
- Reproducible command-line workflows
- QA mindset applied strictly to data integrity

## Best projects to review first

### 1. NYC Yellow Taxi Cleanup
**Repository:** `nyc-yellow-taxi-cleanup`

High-performance data quality pipeline processing **198 million records (60 months of Parquet files)** using Python (Polars). The focus is handling massive-scale data efficiently without memory crashes, keeping suspicious records flagged, comparing years, and avoiding blind deletions.

**Why it matters:**
- Demonstrates ability to process massive datasets (198M+ rows) using high-performance tools like Polars.
- Handles schema drift across multiple years of data.
- Separates real anomalies from records that may still be valid.
- Explains why a data issue may come from source-system changes, not just dirty data.

### 2. Data Quality Audit CLI
**Repository:** `data-quality-audit-cli`

Reusable rule-based validation project for messy CSV and Parquet datasets. Generates reviewable outputs such as summary reports, JSON metrics, HTML output, and exactly flagged rows.

**Why it matters:**
- Shows practical, programmatic data validation logic.
- Focuses on exact affected rows, not vague summaries.
- Can be utilized as a strict data quality gate before import, CRM usage, or business review.

### 3. TED 2025 Data Quality Audit
**Repository:** `ted-2025-data-quality-audit`

Public procurement data quality audit focused on structured data extracted from XML packages. Checks missing amounts, placeholder values, duplicate IDs, and consistency between reported totals.

**Why it matters:**
- Shows data integrity checks on complex, public-sector XML structures.
- Uses validation rules that map directly to real business risks.
- Demonstrates careful treatment of missing and suspicious financial values.

### 4. Customer Data Cleaning
**Repository:** `customer-data-cleaning`

Practical cleanup of messy customer-style data. Useful for showing fundamental deduplication and validation tasks close to everyday business operations.

**Why it matters:**
- Connects directly to common business tasks: CSV/Excel cleanup, missing fields, and formatting standardization.
- Highly communicable and easy to discuss during an interview.

## Secondary Focus (QA / API)

QA/API repositories are maintained as a secondary skill set. They are valuable because data workflows frequently require validating system imports, exports, API endpoints, and expected responses. However, my primary target is structural data validation.

## Target roles

- Junior Data Quality Analyst
- Data Validation Specialist
- Junior Data / SQL Analyst
- Data Support Specialist
- Reporting / SQL Support Analyst
