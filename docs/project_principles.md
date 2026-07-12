# Project Principles

## 1. Catalog, not Destination

Backstage Portal is a catalog, not a destination.

Its purpose is to help users discover, understand and navigate to information—not replace the tools where the work happens.

Whenever possible:

- Documentation remains in the project's repository.
- Source code remains in GitHub.
- Development happens in tools such as Cursor or Claude Code.
- Backstage provides discovery, context and navigation.

The portal should integrate existing tools rather than duplicate their functionality.

---

## 2. Vanilla Backstage First

The portal should initially follow standard Backstage concepts, architecture and user experience.

Prefer built-in Backstage capabilities and established plugins before creating custom solutions.

Custom extensions for vibecoding projects should be added only after the standard developer portal works well.

---

## 3. Documentation is the Product

Every project should contain enough documentation that work can be resumed after weeks or months.

Documentation is a first-class artifact and should evolve together with the product.

---

## 4. Convention over Configuration

Projects should follow a common structure so they can be discovered automatically.

The portal should rely on conventions wherever possible instead of requiring manual configuration.

---

## 5. Grow by Integration

Prefer integrating existing tools over building replacements.

Examples include:

- GitHub
- TechDocs
- AI agents
- MCP servers

The portal should become the entry point into the ecosystem rather than owning every capability.

## Learn Backstage before extending Backstage

Treat the first iterations as a learning phase.

Prefer understanding the standard platform before introducing custom plugins or workflows.

Customizations should solve observed problems rather than anticipated ones.