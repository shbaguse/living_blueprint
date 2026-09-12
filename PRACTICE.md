# Living Blueprint — Practice

This is the default working loop for applying Living Blueprint to real work.

It is a guide for action, not a rigid procedure.

## 1. Understand the work

Identify:

- the actual objective;
- the minimum required outcome;
- known constraints;
- relevant authority;
- what is known;
- what is uncertain.

Do not invent requirements to fill missing information.

## 2. Define the minimum useful result

Determine the smallest result that can meaningfully satisfy the requirement or produce useful evidence.

Avoid solving hypothetical future problems at this stage.

## 3. Build or act

Implement, configure, investigate, or otherwise perform the smallest useful action.

Choose the simplest approach that is capable of producing meaningful progress.

## 4. Run or observe

Whenever possible, execute the work and observe what actually happens.

Use tests, runtime behavior, measurements, inspection, or other appropriate evidence.

Do not assume that successful implementation means successful outcome.

## 5. Record the real gap

Compare the observed result with the required result.

A gap may be:

- failure;
- unexpected behavior;
- limitation;
- missing information;
- incorrect assumption;
- unmet requirement;
- insufficient evidence.

Describe the gap concretely.

## 6. Decide whether further work is justified

Before adding complexity or starting research, ask:

- What specific problem are we solving?
- Why does it matter?
- What evidence do we need?
- Can the question be tested directly?
- What result would change our decision?
- When will we stop?

If the answer does not justify the work, do not continue merely because more work is possible.

## 7. Research or analyze when necessary

Use research or deeper analysis when the real gap requires it.

Prefer targeted investigation over broad exploration.

Research should reduce a meaningful uncertainty, explain an observed problem, compare viable alternatives, or support a consequential decision.

Preserve contradictory evidence.

## 8. Make the smallest justified change

Change the implementation, decision, requirement, or approach according to what the evidence supports.

Do not introduce unrelated improvements merely because they are available.

## 9. Run or verify again

After the change, verify the result.

Where possible, compare the result against:

- the requirement;
- the previous behavior;
- a baseline;
- relevant tests;
- observed evidence.

## 10. Decide the next state

Based on the evidence, choose one:

- keep the result;
- make another targeted change;
- investigate a newly discovered gap;
- simplify or remove unnecessary complexity;
- stop because the requirement is sufficiently satisfied;
- stop because further work is not justified.

## 11. Preserve important knowledge

Record information that is useful for future work, especially:

- decisions and their reasons;
- important evidence;
- failed approaches;
- counter-evidence;
- unresolved uncertainty;
- constraints;
- newly discovered limitations.

Do not record everything merely for the sake of documentation.

## Default loop

For executable work, the default loop is:

    REQUIREMENT
         ↓
       BUILD
         ↓
        RUN
         ↓
      OBSERVE
         ↓
      REAL GAP?
       ↙     ↘
     NO       YES
     ↓         ↓
    STOP    ANALYZE
                ↓
          RESEARCH IF NEEDED
                ↓
             CHANGE
                ↓
              RUN
                ↓
             OBSERVE
                ↓
             REPEAT

## Important rules

Do not:

- research indefinitely before attempting useful work;
- treat hypothetical future needs as current requirements;
- add complexity without a demonstrated reason;
- hide uncertainty;
- ignore contradictory evidence;
- treat implementation as proof of correctness;
- continue work only because significant effort has already been invested.

The objective is not to minimize work.

The objective is to perform the work necessary to produce a sufficiently reliable result, while avoiding unjustified complexity and investigation.
