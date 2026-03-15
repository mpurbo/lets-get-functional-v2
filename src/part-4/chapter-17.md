# Chapter 17 — Monad: Sequencing Effects in Context

> **Placeholder** — This chapter is planned but not yet written.

*Functor + flatten + lawful sequencing. By now they have Functor, and they already use `flatMap` / `bind` daily.*

## Planned Topics

- The problem Monad solves: dependent, sequential computation where each step may change the context
- `flatMap` / `then` / `andThen` — they've been using it; now name it
- The laws (left identity, right identity, associativity) and their practical meaning
- The "M-word" demystified: it's an interface with a specific contract, not a metaphor
- Why lawfulness matters: refactoring guarantees, equational reasoning in real code
