# Chapter 20 — Monad Transformers: The Composition Problem (Introduction)

> **Placeholder** — This chapter is planned but not yet written.

*Stacking effects is genuinely hard. An honest introduction — not a deep dive.*

## Planned Topics

- The problem: `Reader<Result<A>>` vs. `Result<Reader<A>>` — nesting monads breaks `flatMap` ergonomics
- Transformers as one solution: `ReaderT`, `ResultT` — the idea, a small worked example
- The ergonomic cost: type signatures grow, stack depth grows, debugging gets harder
- Alternatives mentioned but not developed: effect systems (Koka, Scala ZIO), tagless final, algebraic effects
- Why this is an introductory chapter: the full treatment is a book in itself
- Guidance: when to reach for transformers, when to just pass parameters
