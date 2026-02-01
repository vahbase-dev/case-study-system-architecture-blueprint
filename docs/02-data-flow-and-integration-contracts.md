# 02 — Data Flow and Integration Contracts

## Goal
Map critical paths and define deterministic contracts between subsystems.

## Data Flow Types
- synchronous request/response for critical operations
- async events for fan-out, enrichment, and long-running tasks

## Contracts
- API contracts (versioned)
- event contracts (schema + compatibility rules)
- idempotency keys for replay-safe processing

## Patterns
- outbox pattern for reliable event publishing
- retries with exponential backoff
- dead-letter queues for poison messages

## Outcome
Clear integration points with reproducible behaviour under retries and replays.
