# Chapter 7 — Modeling Domains with ADTs

> **Placeholder** — This chapter is planned but not yet written.

*Putting it all together: a sustained worked example of domain modeling using products, sums, and pattern matching.*

## Planned Topics

- State machines as ADTs: `State × Event → State` as a pure function over sum types
- Recursive data types: trees, expressions, document structures — types that contain themselves
- Composing ADTs: building complex domains from small, composable type definitions
- The expression problem: adding new cases vs. adding new operations — where ADTs shine and where they pay a cost (honest trade-off with OO polymorphism)
- Worked example: a complete order lifecycle — from creation through fulfillment, cancellation, and refund — modeled as ADTs with exhaustive transitions
