# Chapter 16 — Functor: Computation in Context

> **Placeholder** — This chapter is planned but not yet written.

*"You're already mapping over things."*

## Planned Topics

- `Array.map`, `Optional.map`, `Promise.then`-as-map: the pattern they already use
- The abstraction: transforming the value inside a context without changing the context itself
- The laws (identity, composition) and what breaks when you violate them
- Why a uniform `map` matters: generic programming over any container/context
- Worked example: uniform transformation across Optional, Result, and List in a single pipeline
