# Chapter 4 — Products and Sums: The Two Ways to Combine Types

> **Placeholder** — This chapter is planned but not yet written.

*The foundational vocabulary. Product types combine types with "and"; sum types combine them with "or." Together they can model any domain.*

## Planned Topics

- Product types: tuples, records, data classes — things you already use daily
- Sum types: the missing half — why OO gave you "and" but not "or"
- The cardinality argument: why `Boolean × Boolean` has 4 inhabitants and `Boolean + Boolean` also has 4, but they mean different things
- Sum types across languages: Kotlin sealed class/interface, Swift enum with associated values, TypeScript discriminated unions, Java sealed interfaces (17+)
- The key insight: sum types let you enumerate possibilities; the compiler enforces you handle all of them
