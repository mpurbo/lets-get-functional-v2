# Chapter 12 — State, Visitor, Interpreter → ADTs in Action

> **Placeholder** — This chapter is planned but not yet written.

*Where the ADT foundation from Part II pays off directly. These patterns were working around the absence of sum types and pattern matching.*

## Planned Topics

- The visitor pattern dissolves: sum type + exhaustive match replaces the entire double-dispatch ceremony
- State machines revisited: the `State × Event → State` function from Chapter 7, now in a pattern context
- The interpreter pattern: ADTs as instruction sets, pattern matching as the evaluator — a natural bridge to free monads (mentioned, not developed)
- Honest trade-off: the expression problem surfaces here — adding new cases is easy, adding new operations requires touching every match
- Worked example: order lifecycle state machine (connecting back to the Part II domain model)
