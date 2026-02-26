# Volunteer Wizard — AI-Powered Qualification Engine

![Automation](https://img.shields.io/badge/Tool-Zapier%20Pro-FF4A00?style=flat)
![AI](https://img.shields.io/badge/AI-Zapier%20AI%20%2B%20Perplexity-6366F1?style=flat)
![Status](https://img.shields.io/badge/Status-Production%20Deployed-22c55e?style=flat)
![Steps](https://img.shields.io/badge/Steps-31-c9943a?style=flat)

> **96% faster processing · 80% coordinator time saved · 
> 100% classification consistency · 40% drop-off eliminated**

---

## The Problem

A healthcare nonprofit (alias: HealthCare Connect) was manually 
processing every volunteer application — a 45-minute coordinator 
task per applicant involving credential checks, type classification, 
status routing, and confirmation emails. With growing application 
volume, 40% of applicants were dropping off before completion due 
to slow response times. The process was inconsistent, exhausting 
for staff, and unscalable.

---

## What I Built

A 31-step Zapier automation that handles the full volunteer 
qualification lifecycle autonomously — from application submission 
to confirmed status — in under 2 minutes.

The system uses the **CRAFT methodology** (Context, Role, Action, 
Format, Tone) for all AI prompt design, ensuring consistent and 
auditable outputs at every step.

---

## Workflow Architecture

![Volunteer Wizard Workflow](./workflow-screenshot.png)

### Shared Intake Pipeline (Steps 1–8)
All applications enter a unified pipeline:
- **Step 1:** Form submission triggers workflow
- **Steps 2–4:** Data validation and formatting
- **Steps 5–6:** AI by Zapier — applicant type classification
- **Step 7:** AI classification decision node
- **Step 8:** Route to one of 4 qualification paths

### Path A — Student Volunteers (Steps 9–16)
- Verify enrollment status
- Configure student-tier service assignment
- Send path-specific confirmation email
- Save to coordinator tracker

### Path B — Dental Professional / Direct Support (Steps 10–20)
- Perplexity AI credential verification
- License validation check
- AI confidence report generation
- Configure professional-tier service
- Send credentialed confirmation
- Save with verification record

### Path C — Community Partner / Program (Steps 22–28)
- Filter and validate partner conditions
- AI-assisted organization classification
- Configure partner service tier
- Personalized partner onboarding email
- Save to partner database

### Path D — Unmatched / Needs Review (Steps 22–26)
- Flag for coordinator review
- Assign IT status check
- Create coordinator task in dashboard
- Direct email notification to staff

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Zapier Pro | Workflow orchestration (31 steps) |
| AI by Zapier | Applicant type classification |
| Perplexity AI | Professional credential verification |
| CRAFT Methodology | Prompt design framework |
| Google Sheets | Coordinator dashboard + tracker |
| Gmail | Automated confirmation emails |

---

## Impact

| Metric | Before | After | Change |
|--------|--------|-------|--------|
| Processing time per applicant | 45 min | <2 min | **96% faster** |
| Coordinator time on qualification | 100% | 20% | **80% saved** |
| Classification consistency | Variable | 100% | **Fully consistent** |
| Applicant drop-off rate | 40% | <5% | **Eliminated** |

---

## Methodology: CRAFT

Every AI step in this workflow was designed using the CRAFT framework:

- **C**ontext — what the AI needs to know about the situation
- **R**ole — the expert perspective the AI should take
- **A**ction — the specific task to perform
- **F**ormat — how the output should be structured
- **T**one — the voice and register of the response

This ensures every AI decision in the workflow is auditable, 
consistent, and explainable to non-technical stakeholders.

---

## Privacy Notice

The organization name has been replaced with the alias 
**"HealthCare Connect"** to protect client confidentiality. 
All workflow logic, metrics, tools, and methodology documented 
here are real and reflect the production system as deployed.

---

## What I Would Build Next

- Add a feedback loop that re-trains classification thresholds 
  quarterly based on coordinator override data
- Integrate a Slack notification layer for Path D flagged 
  applicants requiring urgent review
- Build a real-time dashboard in Looker tracking qualification 
  volume, path distribution, and processing time trends

---

*Built by Chrystelle Juste · AI Enablement Strategist · 
[Portfolio](https://notion.so) · [LinkedIn](https://linkedin.com)*
