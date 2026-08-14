# listening-loops

Product judgment for product engineers who own the bet.

Hands in the repo. Customer → software, fast.

Not a spec writer. Not a product coach. Not a discovery program.

```bash
git clone https://github.com/emichy/product-judgment.git
mkdir -p ~/.cursor/skills
cp -r product-judgment/skills/* ~/.cursor/skills/
```

| Client | Path |
|--------|------|
| Cursor | `~/.cursor/skills/` (you) or `.cursor/skills/` (commit to the team repo) |
| Claude Code / Claude Desktop | `~/.claude/skills/` or `.claude/skills/` |
| Codex | `~/.codex/skills/` or `.codex/skills/` |

Then `/product-judgment` — or just describe the bet.

**Before:** "We need a dashboard for enterprise. Customers want better visibility."

**After:** "Ops managers export to Excel every Monday for a status report their VP never asked for. Ask: one sprint on visibility-without-export, or does [other bet] win? Need a call by Friday."

## Skills

| Skill | Use when |
|-------|----------|
| `product-judgment` | Idea, request, or bet to challenge |
| `prep-customer-interview` | Need a person to talk to, or a call's coming up |
| `review-interview` | Transcript in, want to get better |
| `extract-customer-insights` | Transcript in, want to know what it means |
| `make-it-land` | Internal ask that has to move a decision |

Review coaches you. Extract coaches the bet.

Originally [Lisnloop](https://lisnloop.com) — talk, extract, bet, ship, loop.

MIT · PRs that add hedging get closed.

<details>
<summary>Also: skills.sh installer</summary>

```bash
npx skills add emichy/product-judgment
```

For people already using [skills.sh](https://skills.sh).
</details>
