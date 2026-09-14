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

Caprae’s mission is to disrupt and modernize finance by using AI and technology to rebuild how entrepreneurs find, evaluate, acquire, and operate businesses. The company is particularly focused on entrepreneurship through acquisition (ETA) and creating better infrastructure for founders and entrepreneurs.

What stands out to me is Caprae’s willingness to challenge traditional finance rather than simply optimize existing processes. Its approach combines speed, technology, and an entrepreneur-first mindset to reduce manual work and make acquisition processes more efficient.

I see the broader mission as building practical AI infrastructure that helps people make better business decisions while keeping human judgment at the center. That is what makes Caprae’s approach especially interesting to me.

### Why do you want to work at Caprae Capital?

I want to work at Caprae because it combines three areas I am genuinely interested in: AI engineering, entrepreneurship, and real-world business decision-making. I enjoy building AI systems that solve practical problems, especially when the output helps someone make a better decision rather than simply generating information.

The DealSignal challenge gave me a good example of why this interests me. Instead of rebuilding SaaSQuatch’s lead-generation capabilities, I focused on the next problem: helping a searcher turn a large pool of companies into a smaller set of research priorities. I built a deterministic scoring layer, data-coverage indicators, and research recommendations to help decide where limited research time should be spent.

I also want to work in an environment where I can take ownership, move quickly, and work close to business outcomes. Caprae’s founder-first mindset and use of AI to challenge traditional finance make it an environment where I believe I could contribute as an AI engineer while continuing to develop my product and business understanding.

### How is Caprae Changing the ETA Space and Broader PE?

Caprae is changing ETA by applying AI and technology to parts of the acquisition process that have traditionally been highly manual, fragmented, and time-consuming. Instead of relying entirely on spreadsheets, disconnected research, and repetitive analysis, Caprae is building tools that help entrepreneurs discover companies, organize information, evaluate opportunities, and move through the acquisition process faster.

I think the important shift is that technology becomes part of the infrastructure of ETA rather than simply an additional productivity tool. AI can help searchers process larger amounts of information, identify relevant signals, surface gaps, and focus their time on the companies and questions that matter most.

This also has implications for broader private equity. Better data and AI-assisted research can reduce the operational friction around sourcing and analysis, potentially allowing investors and entrepreneurs to evaluate more opportunities without proportionally increasing manual effort. At the same time, the final investment decision remains with the human decision-maker; AI should improve the quality and speed of the research behind that decision rather than replace investment judgment.

### Additional Questions

**Current US working status:**  
I am currently based in Pakistan and do not currently have US work authorization.

**40 hours/week:**  
Yes, I am willing and able to work a minimum of 40 hours per week.

**Why Caprae Capital?**  

Caprae is a strong fit for me because it sits at the intersection of AI, entrepreneurship, and finance. I want to work on AI systems that solve real business problems and have a measurable impact on how people research, evaluate, and operate businesses.

I also connect with Caprae’s bias toward ownership, speed, and experimentation. As someone who has built and shipped AI products end-to-end, I’m most motivated by environments where I can take a problem from understanding the business need through building, testing, and improving the solution.

The opportunity to work closely with entrepreneurs and apply AI to a traditionally manual industry is what makes Caprae particularly compelling to me.

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
