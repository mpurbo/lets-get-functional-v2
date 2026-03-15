# Chapter 22 — Streams as First-Class Architecture

> **Placeholder** — This chapter is planned but not yet written.

*Operators as composed pure functions over time-varying data.*

## Planned Topics

- Operators as higher-order functions: `map`, `filter`, `scan`, `flatMap`, `switchMap` — the vocabulary
- Building declarative pipelines: the topology is the architecture
- The discipline: pure transformations in the middle, effects only at sources and sinks
- Hot vs. cold, unicast vs. multicast: the operational semantics that matter for architecture
- Backpressure as a design concern, not an afterthought
- Worked example: event processing pipeline with error channel and retry
