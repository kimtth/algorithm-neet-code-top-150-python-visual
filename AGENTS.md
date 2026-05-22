
Goal: make the visuals match the actual solutions.

Scope:
- Remove dead code: unused, untested, stale, or unreachable.
- Remove obsolete paths, flags, and duplicate logic.
- Sync docs with the implemented solutions.
- Find and fix contradictions:
  - code vs docs
  - schema/type drift
  - unreachable logic
  - stale assumptions
- Detect design drift from shared/common styles.
- Detect visual drift from the reference solutions.

Rules:
- Prefer deletion over abstraction.
- Prefer existing patterns over new ones.
- Keep fixes small, direct, and local.
- Do not preserve compatibility with obsolete behavior.
- Update docs only to match reality.
- Do not add new features.

Mode: auto-fix.

Output:
1. Summary of fixes.
2. Files changed.
3. Contradictions found and resolved.
4. Remaining risks, if any.