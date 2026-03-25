[← Back to Book](../../README.md) | [↑ Back to Index](../../../../README.md) | [🌐 Switch Language](../ES/02-un-enfoque-pragmatico.es.md)

# 02 - A pragmatic approach

> Quick navigation: [Core idea](#core-idea) · [Key concepts](#key-concepts) · [Actions](#actions) · [Related notes](#related-notes)

## Core idea

Orthogonality reduces friction: when components are well isolated, you can change one without breaking others as long as its interface remains stable. The opposite (non-orthogonal systems) makes change expensive and risky because everything collides with everything.

## Key concepts

- **Orthogonality benefit:** better control, maintainability, and speed of change.
- **Coupling cost:** in non-orthogonal systems, a local decision impacts many other parts.
- **Helicopter example:** even if it looks simple in number of controls, each movement affects other parameters and requires constant compensation.
- **Isolation through interfaces:** if external interfaces stay stable, a component can evolve with lower risk.
- **Third-party dependencies:** every tool or library can add hidden coupling; choose technologies carefully.
- **Decoupled code as discipline:** avoid global data, functional duplication, and overly similar functions.
- **Testing as design signal:** if a unit test needs to import a large portion of the system, decoupling is weak.
- **Reversibility:** assume nothing is permanent; design decisions that can change when context changes.

## Quotes (short only)

- "Nothing is more dangerous than an idea if it is the only one you have."
- "Instead of carving decisions in stone, write them in beach sand."

## My interpretation

This chapter reinforces two habits for me: design to avoid side effects and make decisions expecting change. Orthogonality is not an architectural luxury; it is a practical way to reduce incidents and keep the system evolvable.

## Practical lessons

- Every line of code can increase or reduce coupling, so this impact should be reviewed intentionally.
- If a unit test needs half the system to run, modularity is failing.
- Adopting technology by trend usually makes future changes more expensive.
- Designing for reversibility helps correct direction without rebuilding everything.

## Questions

- Which parts of my system change together because of weak design instead of real need?
- Which third-party libraries are imposing decisions that are hard to reverse?
- How many possible futures does my architecture support today?
- How costly would it be to change a critical decision in six months?

## Actions

- [ ] Review one current module and identify unnecessary coupling between components.
- [ ] Remove at least one global dependency (global state or shared access) in the next iteration.
- [ ] Create or adjust one unit test so it runs with minimal dependencies.
- [ ] Document one important technical decision together with its rollback plan.
- [ ] Continue completing pending notes for the rest of chapter 2.

## Related notes

- Chapter 1: [01 - A pragmatic philosophy](01-a-pragmatic-philosophy.md)
- Preface: [00 - Preface (first edition)](00-preface.md)
- Code review: [09 - Code review](../../../software-engineering-at-google/chapters/EN/09-code-review.md)
- Book index: [The Pragmatic Programmer - README](../../README.md)

## See also

- Chapter template: [chapter-template.md](../../../../templates/chapter-template.md)
- Repository index: [README.md](../../../../README.md)

---

**Navigation**

- Previous chapter: [01 - A pragmatic philosophy](01-a-pragmatic-philosophy.md)
- Next chapter: Planned
- Related notes: [Book README](../../README.md), [Spanish version](../ES/02-un-enfoque-pragmatico.es.md)

## Disclaimer

- These notes are personal interpretations and learning material.
- Any quoted content belongs to its original authors and publishers.
- Quotes are short, attributed when possible, and used for educational purposes.
- This repository does not republish full chapters or substantial copyrighted excerpts.
