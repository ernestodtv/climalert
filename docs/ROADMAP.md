# ClimAlert Roadmap

## Purpose
REST API that consumes real AEMET data, processes it and exposes it 
to detect climate anomalies in Spain.

## Phase 1 — Infrastructure and data
- Docker + PostgreSQL
- AEMET integration
- Basic endpoints
- No TDD, no DDD, no agent mode
- Cursor: Tab and Chat only

## Phase 2 — Testing
- Introduce TDD on business logic
- Integration tests with Testcontainers
- Start using Cursor Composer with criteria

## Phase 3 — Java modern + DDD
- Refactor with design patterns
- Apply DDD consciously
- Explore Cursor agent mode

## Phase 4 — AI integration
- LLM integration for natural language summaries
- Anomaly detection