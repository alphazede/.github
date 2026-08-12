## AlphaZede

**Keeping your team aligned, with AI contained by infrastructure—not promises.**

Coding agents fail in two directions. Most of the time they drift — building
something adjacent to what your team actually meant. Occasionally they do
something nobody sanctioned. The first problem is alignment. The second is
containment. They need different machinery, and we build both.

The people who block agent adoption inside a company are rarely the juniors.
They're the engineers who've shipped for twenty years and won't hand a
repository to a process they can't inspect, bound, or audit. We build for that
engineer: everything runs on your machines, scope is approved before work
starts, and what happened afterward is a record you can read.

### Shipping now

**[Bearing Lite](https://github.com/alphazede/bearing-lite)** — a skills-first
Agent Plugin for planning, routing, bounded execution, and independent review.
It preserves human authority and reviewable handoffs without shipping a CLI,
MCP server, browser control room, or hidden runtime state.

```sh
npm pack @alphazede/bearing-lite
```

Install it through a compatible Agent Plugin client. The portable package is
[`@alphazede/bearing-lite`](https://www.npmjs.com/package/@alphazede/bearing-lite).

**[BRAN](https://github.com/alphazede/bran)** — local repository intelligence.
Deterministic scanning, focused evidence packets, validation, and offline
browsing. Headless for scripts and agent workflows, with an optional terminal
interface for reading. Scanning and validation need no agent account.

### How we build

- Deterministic checks decide. A model may recommend; it never holds sole
  authority.
- Fail closed when a required check can't run.
- Evidence is reviewable after the fact, or it isn't evidence.

We don't claim an agent can't misbehave. We claim it can't get far.

---

[alphazede.com](https://alphazede.com) · Austin, TX
