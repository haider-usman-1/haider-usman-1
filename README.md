# Haider Usman

Backend and systems engineer in Lahore. I work on the parts of a system where being
wrong is expensive, and on the guardrails that stop automated pipelines from lying
about their own results.

### What I work on

- **Django / DRF / Postgres** on a mid-size ERP — payroll, costing, and settlement
  paths, where a rounding error is somebody's salary.
- **Containment and verification for autonomous coding agents** — filesystem
  write-scoping, refusing package installs and destructive git operations,
  deterministic phase replay, and catching the run that reports success on work it
  did not actually do.
- **Small local-first tools**, shipped as a single executable with no toolchain to
  install.

### Selected work

**[Digital-Invoicing](https://github.com/haider-usman-1/Digital-Invoicing)** — files
sales invoices to Pakistan's FBR Digital Invoicing system. A pure core with no I/O
for the rules that are expensive to get wrong, a mock mode that can be told to fail
in each of FBR's real failure shapes, and a roadmap that records which of FBR's
undocumented behaviours have been verified against a production filing and which are
still assumptions.

### How I work

Assumptions get written down next to the file they live in, along with whether
they've been verified and what would settle them. Most of what I've learned the hard
way is in the roadmaps and comments rather than the commit messages.
