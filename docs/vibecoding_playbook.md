# Vibecoding Playbook

This document describes how to run a project using this template.

For stable principles, read:

```text
docs/core_principles.md
```

---

## Purpose

Help build useful software in small, product-oriented iterations.

The goal is not to write as much code as possible.

The goal is to make good product decisions and create visible user value.

---

## Project Flow

Use this flow:

```text
Product foundation
        ↓
Discovery
        ↓
Backlog
        ↓
Build one small feature
        ↓
Definition of Done
        ↓
Next backlog item
```

---

## Product Foundation

Before implementation, make sure these documents exist and are usable:

```text
docs/product_description.md
docs/project_principles.md
```

The product description should answer:

- What problem are we solving?
- Who is it for?
- Why is it valuable?
- What is the MVP?

Project principles should contain only decisions unique to this project.

---

## Discovery

Before building a new idea, challenge it.

Use:

```text
docs/product_discovery_template.md
docs/discovery_canvas.md
```

Ask:

- What must be true for this to be valuable?
- How could we be wrong?
- What is the smallest experiment that can teach us something?
- Can we reduce scope before implementation?

---

## Backlog

Use:

```text
docs/backlog.md
```

The backlog should focus on the next few iterations only.

Prioritize:

- User value
- Risk reduction
- Small scope
- Visible progress

Avoid building a complete long-term feature plan too early.

---

## Implementation

Before implementation, use:

```text
docs/coach_checklist.md
```

Then build one small feature, problem or decision at a time.

Prefer:

- Focused changes
- Existing patterns
- Simple architecture
- Clear naming
- Manual validation when that is enough

Avoid:

- Large rewrites
- Scope creep
- Premature optimization
- Solving future problems too early

---

## Decisions

Use:

```text
docs/decision_log.md
```

when a decision affects:

- Product direction
- Architecture
- Integrations
- Data model
- Scope
- Tool choice
- Important tradeoffs

Do not document every small implementation detail.

---

## Done

Use:

```text
docs/definition_of_done.md
```

before considering a task complete.

A task is done when the user can see or verify the intended improvement.

---

## Template Improvements

If something should improve the template itself, add it to:

```text
docs/template_backlog.md
```

Do not mix template improvements into the product backlog.
