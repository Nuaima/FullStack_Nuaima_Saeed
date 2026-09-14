# Product Decisions

## Why not build another scraper?

SaaSQuatch already focuses on company discovery and enrichment.

The higher-value problem is deciding which discovered companies
deserve limited research time.

## Why deterministic scoring?

Search-fund and acquisition research requires traceability.
A searcher should be able to understand why a company received
a particular priority.

## Why use an LLM only for the research brief?

LLMs are useful for synthesizing evidence and identifying
research questions, but the core ranking should remain
auditable.

## Why not build CRM functionality?

The challenge allows limited implementation time. CRM,
outreach automation, authentication, and additional scrapers
would dilute the core research-prioritization workflow.

## Why CSV?

CSV provides a simple interface between existing lead-generation
workflows and DealSignal without requiring a proprietary API
integration.
