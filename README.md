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

## Author

Nuaima Saeed  
AI Engineer

Portfolio: YOUR_PORTFOLIO_URL
LinkedIn: YOUR_LINKEDIN_URL
GitHub: YOUR_GITHUB_URL
