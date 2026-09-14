# DealSignal

> Acquisition Research Intelligence

## 🚀 Live Demo

[Open DealSignal](https://fullstacknuaima.netlify.app/)

## Problem

SaaSQuatch can help searchers discover and enrich large numbers
of companies. The next bottleneck is deciding which companies
deserve deeper research.

DealSignal addresses that decision layer.

## Product Thesis

SaaSQuatch finds companies  
→ DealSignal prioritizes research  
→ Research Brief identifies what to investigate next.

## Key Features

- Deterministic Research Priority scoring
- Data Coverage measurement
- Ranked target list
- Company Explorer
- Signal breakdown
- Research Brief
- Data-gap identification
- CSV upload
- Ranked CSV export

## Research Priority

| Signal | Weight |
|---|---:|
| Operating History | 25 |
| Capital Profile | 25 |
| Company Size | 25 |
| Digital Opportunity | 25 |

## Important Caveat

The Research Priority score is a prioritization mechanism.
It is not a prediction of acquisition suitability, valuation,
owner willingness, or investment attractiveness.

## Demo Dataset

The included dataset is synthetic and is provided only to
demonstrate the product workflow.

## Architecture

CSV / SaaSQuatch Export
        ↓
Normalization
        ↓
Research Priority Engine
        ↓
Data Coverage
        ↓
Ranked Targets
        ↓
Research Brief
        ↓
Searcher's Next Action

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Client-side CSV processing
- Netlify

## Future Production Architecture

SaaSQuatch Export
        ↓
FastAPI
        ↓
Normalization / Deduplication
        ↓
Deterministic Priority Engine
        ↓
Evidence & Enrichment
        ↓
LLM Research Brief
        ↓
Supabase / PostgreSQL
        ↓
DealSignal Dashboard

## Limitations

- Demo uses synthetic data
- No live SaaSQuatch API integration
- Research Brief is rule-based in this prototype
- Source verification is not yet automated
- Score does not establish acquisition suitability

## Business Understanding

### What is Caprae's Mission?

[Your answer]

### Why do you want to work at Caprae Capital?

[Your answer]

### How is Caprae Changing the ETA Space and Broader PE?

[Your answer]

### Additional Questions

**Current US working status:**  
I am currently based in Pakistan and do not currently have US work authorization.

**40 hours/week:**  
Yes, I am willing and able to work a minimum of 40 hours per week.

**Why Caprae Capital?**  
[Your answer]

**Expected salary:**  
I am open to discussing compensation based on the role, responsibilities, and overall opportunity.

### Employment Expectations

I understand and am comfortable with the 3-month probationary period, the 9AM–6PM EST schedule with a 1-hour lunch during the initial 2–3 month training period, and occasional off-hours availability for customer emergencies or time-sensitive projects. This would not be an issue for me.

## Author

Nuaima Saeed  
AI Engineer

Portfolio: https://nuaima-portfolio.netlify.app/
LinkedIn: https://www.linkedin.com/in/nuaimasaeed/
GitHub: https://github.com/Nuaima
