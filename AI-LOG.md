# AI-LOG.md

## 2026-10-07 — IA#1 cartTotal: rules file, CI, brief, implementation, tests

Tool: Kiro (AI assistant, Kiro IDE).

Asked for: (1) create a project rules file (CLAUDE.md) for the starter repo based on the root CLAUDE.md behavioral guidelines and the README spec; (2) create a GitHub Actions CI workflow; (3) write a BRIEF.md naming files, contract, error cases, and no-dependencies constraint; (4) implement `cartTotal` in `src/cart.js`; (5) write tests in `test/cart.test.js` covering all rubric cases.

Kept: the full implementation of `cartTotal` — validation loop, empty-cart early return, `reduce` for subtotal, `Math.round` for the return value; the CI workflow as generated; the BRIEF.md as generated; all 6 tests as generated.

Changed: nothing rewritten — reviewed each file before accepting and the logic matched the spec on first read.

Rejected: nothing thrown away from this session.

By hand: the prompts directing each step — reading the rubric and slides first, deciding the order of work (harness → brief → implement → test), specifying the exact rules file content needed, and verifying that `cartTotal(...) === 467400` held with strict equality before accepting the implementation.
