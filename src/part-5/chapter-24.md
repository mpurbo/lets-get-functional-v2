# Chapter 24 — Side Effects at the Edge

> **Placeholder** — This chapter is planned but not yet written.

*The "imperative shell / functional core" pattern applied to reactive systems.*

## Planned Topics

- The principle restated for streams: sources and sinks are the imperative shell; everything between is pure
- Subscription management and resource lifecycle: the practical reality of reactive systems
- Testing strategy: pure pipeline logic tested in isolation, integration tests only at the edges
- Error handling at the boundary: where to catch, where to retry, where to dead-letter
- The connection back to Part I: this is what "separating computation from effect" looks like at system scale
