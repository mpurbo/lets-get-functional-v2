# Chapter 23 — Pipeline-Oriented Architecture

> **Placeholder** — This chapter is planned but not yet written.

*Railway-oriented programming meets streams.*

## Planned Topics

- The `Result`/`Either` monad from Part IV applied to stream pipelines: error channels as first-class citizens
- Composing subsystems as stream topologies: each subsystem is a function `Stream<A> → Stream<B>`
- Splitting and merging: fan-out, fan-in, broadcast, partitioning
- Designing for observability: tapping pipelines without mutating them
- Worked example: order processing system as composed stream subsystems
