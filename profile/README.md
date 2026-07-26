## AlphaZede

**Lower the barrier to entry for your team. Keep your IP inside it.**

Coding agents are only worth deploying if the people who need them can actually
use them, and only safe to deploy if your source stays under your control. Most
teams get one or the other.

We build for both. Our tools run on your machines, keep planning and evidence in
your repository, and hold agents to a scope you approved before work started —
so an engineer who isn't an agent expert can still get bounded, reviewable work
out of one.

### Products

**[Bearing](https://github.com/alphazede/bearing)** — a local browser control
room for evidence-backed agent work. It turns a complex repository request into
an approved plan, bounded execution, owner decisions, and reviewable evidence,
without surrendering approval or review authority to the agent.

```sh
npm install --global @alphazede/bearing
bearing start
```

**[BRAN](https://github.com/alphazede/bran)** — local repository intelligence.
Deterministic scanning, focused evidence packets, validation, and offline
browsing. Headless for scripts and agent workflows, with an optional terminal
interface for reading. Scanning and validation need no agent account.

### How we build

- Deterministic checks decide. A model may recommend; it never holds sole
  authority.
- Fail closed when a required check can't run.
- Evidence is reviewable after the fact, or it isn't evidence.

---

[alphazede.com](https://alphazede.com) · Austin, TX
