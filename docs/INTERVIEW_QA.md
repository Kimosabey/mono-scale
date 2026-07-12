# Interview Q&A — MonoScale

### "Tell me about this project."
MonoScale is a modular monolith that scales like services but ships like one app. MonoScale is a NestJS modular monolith with strict module boundaries, so features stay decoupled and any module can be extracted into its own service later without a rewrite.

### "What was the hardest part?"
Enforcing boundaries in a monolith so it keeps the option of splitting without the cost of distributing early.

### "Why did you choose this stack?"
- **NestJS** — structured typescript backend.
- **TypeScript** — type-safe application code.

### "How does it fit the rest of your portfolio?"
It follows my "Antigravity" model — local logic/state/UI, cloud reasoning where it earns its cost — and shares the documentation and deployment conventions used across all my projects (#38).
