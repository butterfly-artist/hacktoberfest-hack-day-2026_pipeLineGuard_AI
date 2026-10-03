# PipeGuard AI

## Team / attendee

- Team name (if applicable): N/A — Solo participant
- Members and GitHub usernames:
  - Thota Madhulika — `@butterfly-artist`
- Profile links (optional):
  - GitHub: https://github.com/butterfly-artist

## Challenge

Select the challenge you are entering:

- [x] Best Open-Source AI Project
- [ ] Best Use of Gemma 4
- [ ] Build on elah

## Project links

- Public GitHub repository:
  - [REPLACE WITH FINAL PUBLIC PIPEGUARD GITHUB REPOSITORY]
- Open-source license (link to the license file):
  - MIT License — [REPLACE WITH FINAL LICENSE LINK]

## Problem and solution

### Who is this for?

PipeGuard AI is designed for Data Engineers, Analytics Engineers, ML Engineers, Data Platform Engineers, and developers who work with data pipelines.

### What problem does it solve?

Modern data pipelines can fail because of schema mismatches, missing values, duplicate records, invalid data types, broken references, inconsistent formats, invalid business values, and transformation failures.

Traditional data-quality systems can identify that a rule failed, but engineers often still need to determine:

- Why did the pipeline fail?
- What data caused the failure?
- Which columns or entities are affected?
- What downstream data may be impacted?
- What should the engineer do next?
- What quality rule could prevent the same failure?

PipeGuard AI combines deterministic data-quality computation with open-weight AI reasoning to answer these questions from actual data evidence.

### Main input → output workflow

```text
Dataset
(CSV / JSON / Parquet)
        |
        v
Data Ingestion
        |
        v
Deterministic Data Profiler
        |
        v
Schema + Relationship Detection
        |
        v
Data Quality Rule Engine
        |
        v
Pipeline Log Context
        |
        v
Context Engine
        |
        v
Gemma Open-Weight AI
        |
        v
Evidence-Grounded Diagnosis
        |
        +----> Root Cause
        |
        +----> Impact Analysis
        |
        +----> Remediation
        |
        +----> Reusable Quality Rules
