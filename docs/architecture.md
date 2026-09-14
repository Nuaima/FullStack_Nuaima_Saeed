# Architecture

## Current Prototype

Browser
  ↓
index.html
  ↓
JavaScript scoring engine
  ↓
Client-side dashboard

CSV
  ↓
CSV parser
  ↓
Normalization
  ↓
Scoring
  ↓
Dashboard

## Production Architecture

SaaSQuatch
    ↓
FastAPI
    ↓
Normalization
    ↓
Deduplication
    ↓
Validation
    ↓
Research Priority Engine
    ↓
Evidence Layer
    ↓
LLM Research Brief
    ↓
PostgreSQL / Supabase
    ↓
Dashboard
