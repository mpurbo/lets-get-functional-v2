# Chapter 3 — Immutability as Architecture

> **Placeholder** — This chapter is planned but not yet written.

*Not just `const` everywhere — why immutable data changes how you reason about state, concurrency, debugging, and system boundaries.*

## Planned Topics

- The hidden cost of mutation: action at a distance, defensive copying, "who changed this?"
- Structural sharing and persistent data structures: how immutability can be efficient
- The performance conversation, honestly: when copying is fine, when it isn't, and how to measure
- Immutability at the system boundary: event sourcing as the natural extension
- Direct comparison: mutable stateful object vs. immutable data + pure transformation pipeline
