# Chapter 19 — The Monads You Haven't Met Yet

> **Placeholder** — This chapter is planned but not yet written.

*Reader, Writer, State — practical examples in Kotlin, Swift, TypeScript. Not Haskell.*

## Planned Topics

- **Reader**: dependency injection without the framework
  - Shape: `Environment → A`
  - Use case: passing config/context through a call chain without parameter drilling
  - Building a small Reader in TypeScript/Kotlin (30 lines, no library)
- **Writer**: structured logging and audit trails
  - Shape: `(A, Log)` accumulated monadically
  - Use case: pure functions that produce an audit trail
- **State**: threading state through pure computation
  - Shape: `State → (A, State)`
  - Use case: parsers, interpreters, simulations
- Honest trade-off: ergonomics in languages without do-notation — for-comprehensions, chain methods, and their limits
