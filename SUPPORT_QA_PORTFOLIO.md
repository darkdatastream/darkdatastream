# Support / QA API Portfolio

This page is a short index of projects most relevant to Application Support, Technical Support, Product Support, Junior QA/API Tester, and SQL/Data Support roles.

The focus is practical troubleshooting: tickets, API behavior, expected vs actual results, reproducible checks, clear evidence, and escalation-ready notes.

## Positioning

I am transitioning into technical IT work through support-style investigation, API validation, and data quality checks.

I am not presenting myself as a senior developer, automation QA engineer, DevOps engineer, or infrastructure owner. My entry-level strength is careful investigation: reproduce the issue, check the evidence, compare expected vs actual behavior, document the result, and escalate clearly when needed.

This is an AI-assisted and manually reviewed portfolio. I use AI tools for scaffolding, edge-case thinking, and review support, but the goal is evidence-based validation rather than unsupported claims.

## Core practices shown

- API smoke testing and response validation
- HTTP status code checks and negative scenarios
- JSON field validation
- Postman/API exploration
- pytest + requests checks
- Clear bug reports with expected vs actual behavior
- Requirement → test case → test/evidence traceability
- SQL/data investigation basics
- Row-level data quality flags
- Reproducible command-line workflows
- CI-visible checks where applicable

## Best projects to review first

### 1. Buggy Shop QA Practice
**Repository:** `buggy-shop-qa-practice`

Controlled QA/API practice target with requirements, manual test cases, traceability matrix, example bug reports, Postman collection, pytest tests, GitHub Actions CI, lightweight security scan, and privacy notes.

**Why it matters:**
- Shows a complete QA flow from requirement to evidence.
- Demonstrates API exploration, JSON validation, negative testing, and bug reporting.
- Includes traceability between requirements, test cases, automated checks, and known defects.

### 2. GitHub API Smoke Monitor
**Repository:** `github-api-smoke-monitor`

Lightweight API smoke test project using Bash, curl, jq, and GitHub REST API responses.

**Why it matters:**
- Checks HTTP status codes, selected JSON fields, headers, and a negative scenario.
- Shows basic API troubleshooting without a large framework.
- Includes a real learning point: a JSON boolean value `false` is valid data and should not be treated as missing.

### 3. Data Quality Audit CLI
**Repository:** `data-quality-audit-cli`

Reusable validation tool for messy CSV/Parquet data with YAML-defined rules, flagged rows, Markdown/JSON/HTML reports, tests, and CI.

**Why it matters:**
- Connects support-style investigation to data integrity.
- Shows exact affected rows, not only vague summaries.
- Useful for roles where issues come from imports, exports, reports, CRM data, or business system feeds.

### 4. Application Support Ticket Lab
**Repository:** `qa-ticket-lab-private`

Simulated support incident documentation: tickets, logs, SQL checks, API investigation, root-cause notes, workaround notes, and escalation-ready summaries.

**Why it matters:**
- Models the kind of written investigation expected in Application Support.
- Focuses on evidence and escalation rather than guessing.
- Shows how API/data/log evidence can be converted into a clear support note.

## Not claiming

- Senior QA automation experience
- Production incident ownership
- DBA-level SQL/database administration
- Linux system administration ownership
- DevOps/SRE responsibility
- Advanced JavaScript/TypeScript automation ownership

## Target roles

- Application Support Specialist
- Technical Support Engineer
- Product Support Specialist
- Junior QA / API Tester
- Data Support Specialist
- SQL Support Analyst
- Data Quality Analyst
