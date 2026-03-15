# Chapter 8 — ADTs Without Language Support

> **Placeholder** — This chapter is planned but not yet written.

*For teams working in languages where ADTs are partial, awkward, or absent. Pragmatic strategies and their costs.*

## Planned Topics

- TypeScript: discriminated unions are genuine sum types — the best story outside ML-family languages
- Kotlin: sealed hierarchies are expressive but verbose compared to ML-style ADTs
- Swift: enums with associated values are close to the ideal but interact awkwardly with protocols
- Java: sealed interfaces (17+) plus records (16+) get you there, with ceremony
- JavaScript: runtime tag checks and the discipline required to make them safe
- Library-assisted approaches: what fp-ts, Arrow, and similar libraries add
- The honest cost: when fighting the language isn't worth it
