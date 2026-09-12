# Living Blueprint — Unknown

UNKNOWN means that the available evidence is not sufficient to establish an answer.

UNKNOWN is a valid state.

## What UNKNOWN means

When something is unknown:

- do not silently convert it into YES;
- do not silently convert it into NO;
- do not present an assumption as a fact;
- do not fill the gap merely to make the work appear complete.

UNKNOWN should remain explicit until sufficient evidence changes its status.

## UNKNOWN is not a reason to continue

An unknown does not automatically justify more research, more implementation, or more complexity.

Further investigation is justified only when:

1. the unknown matters to the actual objective or decision;
2. there is a meaningful question that can be investigated;
3. useful evidence can reasonably be obtained;
4. the expected value of resolving the unknown justifies the cost.

Otherwise, the work may proceed with the unknown explicitly preserved, or stop.

## Handling an unknown during real work

When an unknown is encountered:

    UNKNOWN
       ↓
    Does it matter?
       ↓
      NO ─────────→ Preserve / Stop
       │
      YES
       ↓
    Can it be tested or investigated?
       ↓
      NO ─────────→ Preserve UNKNOWN
       │
      YES
       ↓
    Investigate / test
       ↓
    Obtain evidence
       ↓
    Update the state

The result may be:

- established;
- disproven;
- narrowed;
- still unknown.

A failed attempt to resolve an unknown is itself useful evidence when accurately recorded.

## Stopping condition

Do not investigate indefinitely.

Stop when:

- the unknown no longer affects the decision;
- sufficient evidence has been obtained;
- available evidence cannot reasonably resolve it;
- further investigation costs more than the expected value;
- or the original objective has already been sufficiently satisfied.

## Important distinction

UNKNOWN is different from:

- lack of documentation;
- lack of confidence;
- disagreement;
- hypothesis;
- assumption;
- untested implementation.

These may contribute to an unknown state, but they are not automatically equivalent to UNKNOWN.

## Evolution

The handling of UNKNOWN should evolve only when real use demonstrates that the current treatment is insufficient.

Do not add categories or procedures merely because they might become useful in the future.
