# Chapter 18 — The Monads Hiding in Your Codebase

> **Placeholder** — This chapter is planned but not yet written.

*Show how each familiar type is a monad, what guarantees that gives, and what they've been doing "by hand" that the abstraction handles.*

## Planned Topics

- Optional / Maybe — short-circuit on absence
- Result / Either — short-circuit on failure (railway-oriented programming introduced here)
- List — nondeterminism / multiple results
- Promise / Future — asynchronous sequencing
- For each: the monad interface, how they already use it, what they gain by recognizing it
- The common shape: `flatMap` chains as programs that describe sequential, context-dependent computation
