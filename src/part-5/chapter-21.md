# Chapter 21 — From Request-Response to Dataflow

> **Placeholder** — This chapter is planned but not yet written.

*The mental model shift: programs as topologies of data transformation, not sequences of commands.*

## Planned Topics

- The imperative default: fetch → process → respond, step by step
- The dataflow alternative: declare what transforms what, let the runtime handle sequencing
- Why this matters now: event-driven systems, real-time data, distributed architectures
- The connection to FP: streams are functors (map), monads (flatMap), and monoids (merge/concat)
- A small but complete example: request-response service rewritten as a stream topology
