# Job Match & CV Tailoring Workflow

This document turns your notes into a practical, repeatable process you can run with an AI assistant.

## 1) Upload CV and request a skill assessment

Use this prompt:

> Assess my CV and extract:
> - Technical skills (tools, languages, frameworks)
> - Product/data/engineering competencies
> - Seniority indicators (ownership, scope, leadership)
> - Years of experience evidence by skill area
> - Gaps for target roles in Singapore
>
> Output as:
> 1. Skills matrix (skill, evidence, confidence)
> 2. Strengths summary
> 3. Missing skills by role type (Marketing, Data, Customer Success, Growth)

## 2) Search for Singapore jobs using target-role filters

Use this prompt:

> Find jobs in Singapore with these requirements:
> - Job title must include at least one keyword: marketing, data, customer success, growth, korean market
> - Prioritize roles involving Korea/Korean-speaking market expansion, partnerships, or regional GTM
> - Include role level, company, location, URL, posted date, and source platform
> - Search across LinkedIn, Google Careers, company career sites, and Glassdoor
> - Exclude duplicates and expired postings
>
> Return a table with: title, company, location, source platform, posted date, salary (if available), source URL.

## 3) Score CV against each JD

Use this prompt:

> Compare my CV against each job description and provide:
> - Match score (0-100)
> - Skill match (required vs present)
> - Experience match
> - Domain/industry match
> - Korean market relevance match
> - Risks/gaps
> - Recommendation: Apply / Stretch / Skip
>
> Return ranked output from highest to lowest fit.

## 4) Tailor CV per target role and verify formatting

Use this prompt:

> Tailor my CV for the selected job. Keep layout and formatting exactly the same; only update content.
> Then:
> 1. Generate PDF
> 2. Run a final QA check to confirm formatting consistency
> 3. List all changed lines/sections

### QA checklist before applying

- Header/contact unchanged
- Typography and spacing unchanged
- Bullet alignment unchanged
- No fabricated achievements
- Keywords inserted only where truthful
- Korean market statements are supported by past experience
- PDF exports cleanly and is readable on desktop/mobile

## 5) Application execution

Use this prompt:

> Prepare application packets for the shortlisted jobs:
> - Tailored CV PDF
> - Customized short cover note
> - Tracker row with status and timestamp
> - Source platform (LinkedIn / Google Careers / Company site / Glassdoor)
>
> Before submission, ask for final confirmation.

> **Important:** Mass auto-apply can violate platform terms and may reduce quality. Prefer a controlled batch process (e.g., top 10-20 strong matches) with final human approval.

## Suggested output schema

For each job:

- Job ID / URL
- Source platform
- Match score
- Must-have skills met (%)
- Nice-to-have skills met (%)
- Experience fit
- Korean market relevance fit
- Tailoring status (Not started / Drafted / QA passed / Submitted)
- Final recommendation

