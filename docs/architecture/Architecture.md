# Career Intelligence Architecture

Career Intelligence is designed as a plugin within the IntelligenceOS ecosystem.

## High-Level Flow

```text
Job Posting
    ↓
AI Analysis
    ↓
Resume Match Score
    ↓
Keyword Analysis
    ↓
Interview Preparation
    ↓
Store Results
    ↓
Dashboard
```

## Core Components

- Career Master
- Resume Generator
- Job Posting Analyzer
- ATS Scoring Engine
- Keyword Intelligence
- Interview Generator
- Career Dashboard

## Design Principles

- Keep Career Master as the single source of truth.
- Generate resume variants from Career Master.
- Store job posting analysis results for future learning.
- Keep AI logic reusable for future IntelligenceOS plugins.
