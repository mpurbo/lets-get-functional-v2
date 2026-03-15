# Chapter 6 — Making Illegal States Unrepresentable

> **Placeholder** — This chapter is planned but not yet written.

*The design philosophy that changes how you think about domain modeling. Not just a technique — a shift in what you consider the job of a type definition.*

## Planned Topics

- The idea: if a state can't be constructed, it can't cause a bug at runtime
- Parse, don't validate: transforming unstructured input into typed, invariant-preserving structures at the boundary
- Newtypes / branded types: making `CustomerId` and `OrderId` non-interchangeable
- Smart constructors: functions that return `Result<T>` instead of `T`
- Worked example: a payment domain where invalid states (negative amounts, mismatched currencies, completed-but-unfunded) are structurally impossible
