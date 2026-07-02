# Application Workflow

## Purpose

Create a repeatable job application workflow that favors speed, volume, and learning while still capturing enough information to improve resumes, interview preparation, and Career Intelligence analytics over time.

---

## Manual Workflow v0.1

### Step 1: Search LinkedIn

Use targeted searches such as:

- Software Director remote Easy Apply
- Director of Engineering remote Easy Apply
- Director Software Engineering Java remote
- Engineering Director AI remote
- Senior Engineering Manager remote Easy Apply

Recommended filters:

- Remote
- Easy Apply
- Under 10 applicants
- Posted recently
- Cloud / SaaS / Java / AWS / Azure when useful

---

### Step 2: Fast Screen the Headline

Before reading the full posting, scan:

- Title
- Company
- Remote status
- Applicant count
- Easy Apply availability
- Seniority level
- Technology hints

Decision:

- Apply fast
- Save for later
- Skip

---

### Step 3: Capture Job Posting

If the role looks relevant, save the posting under:

```text
data/job_postings/<Company>/<YYYY-MM-DD-role-title>.md
```

Minimum fields:

- Company
- Title
- Location
- Application type
- Requirements
- Responsibilities
- Match notes
- Application status

---

### Step 4: Apply

Use the best matching resume:

- Resume A: Director of Engineering / Director Software Engineering
- Resume B: Senior Engineering Manager
- Resume C: Engineering Manager / Principal Engineer

For strong matches, attach a short cover letter when LinkedIn allows it.

---

### Step 5: Track Outcome

Update the posting file with:

- Applied date
- Resume used
- Recruiter contact
- Follow-up status
- Interview status
- Rejection / ghosted / interview / offer

---

## Future Automation

Later versions will support:

- Job posting parser
- Resume match score
- Keyword extraction
- ATS score
- Application dashboard
- Recruiter tracking
- Interview preparation generator
