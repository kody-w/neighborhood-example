# Neighborhood Example

A planted RAPP neighborhood. Local-first workflow + per-operator front doors + sha256-pinned agents + sneakernet-portable.

## Get set up in one chat

You have a brainstem running and the `egg_hatcher_agent.py` in your `agents/` directory.

**From the egg you received:**
```
EggHatcher from_egg=/path/to/neighborhood-example.egg
```

**Or from this repo (if you have GitHub access):**
```
EggHatcher from_repo=kody-w/neighborhood-example
```

That's it. The bootstrap unpacks, sha256-verifies, installs all workflow agents, mints your rappid + per-handle workspace + local data dir, records the subscription. ONE chat, complete setup.

## Reading order

1. [`onboarding.html`](onboarding.html) — friendly visual entry
2. [`QUICK_START.md`](QUICK_START.md) — 1-page reference
3. [`SETUP.md`](SETUP.md) — all three setup modes (egg / repo / pack)
4. [`SKILL.md`](SKILL.md) — feed to your LLM to drive setup
5. [`CONSTITUTION.md`](CONSTITUTION.md) — 8 articles governing this neighborhood
6. [`specs/`](specs/) — the agent contract, neighborhood protocol, manifest format

## Identity

- **Rappid:** see `rappid.json`
- **Owner:** `kody-w`
- **Slug:** `neighborhood-example`
- **Visibility:** see `neighborhood.json` (`visibility` field)
- **Parent:** [kody-w/RAPP](https://github.com/kody-w/RAPP) (the kernel)
