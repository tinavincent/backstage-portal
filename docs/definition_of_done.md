# Definition of Done

Use this checklist before considering a task complete.

Keep it lightweight. The goal is quality and clarity, not process for its own sake.

---

## Product

- The change supports the agreed user goal.
- The scope matches the agreed smallest useful version.
- The result is visible or testable by the user.

---

## UX

- The user can understand what changed.
- The next action is clear.
- Loading, success and error states are handled when relevant.
- Labels use product language, not internal system language.

---

## Code

- The implementation is focused.
- Existing behavior is preserved unless explicitly changed.
- Naming is understandable.
- Obvious duplication or unnecessary complexity has been avoided.
- No unrelated refactoring was included.

---

## Validation

- The changed flow has been manually tested.
- Important edge cases have been checked.
- Errors are handled well enough for the current scope.
- If automated tests exist, relevant tests pass.

---

## Documentation

Update only what is relevant.

Consider whether any of these need updates:

- `docs/backlog.md`
- `docs/product_description.md`
- `docs/project_principles.md`
- `docs/decision_log.md`
- `docs/template_backlog.md`

---

## Git

Before finishing:

- Review the diff.
- Commit focused changes.
- Push when ready.

---

## Final Check

The work is done when the answer to this question is yes:

> Can the user see or verify the intended improvement without needing extra explanation?
