# product-judgment

Product judgment for product engineers who own the bet.

Paste a feature request, a transcript, or "who should I talk to." You leave with the bet, who to call, what to ask, or the message that unblocks.

Customer → software, fast.

**Before:** "We need a dashboard for enterprise. Customers want better visibility."

**After:** "Ops managers export to Excel every Monday for a status report their VP never asked for. Ask: one sprint on visibility-without-export, or does [other bet] win? Need a call by Friday."

## Install

### 1. As a Plugin

The plugin is how Claude and Cursor keep skills up to date. Install it once, get updates after that.

**Claude Code** — run these one at a time; the first registers the marketplace, the second installs from it:

1. `/plugin marketplace add emichy/product-judgment`
2. `/plugin install product-judgment@product-judgment`

**Claude Desktop / claude.ai** — **Customize → Plugins → Add → Add marketplace → Add from a repository**. Paste `https://github.com/emichy/product-judgment`, **Sync**, then open **Product Judgment** and **Install**.

**Cursor** — **Customize → Plugins → Add Marketplace → Import from Github**. Paste the same URL, then install **Product Judgment**. Leave **Auto Refresh** on and updates arrive on their own.

Updating later: `/plugin marketplace update product-judgment` then `/plugin update product-judgment@product-judgment` in Claude Code; the **Update** button in Claude Desktop and Cursor.

Installed as a plugin, the skills are namespaced — `/product-judgment:make-it-land`. Ugly, and that's how Claude plugins work.

### 2. Anyone — one command

Works everywhere, Codex included:

```bash
npx skills add emichy/product-judgment
```

Via [skills.sh](https://skills.sh). No plugin UI required.

### 3. Manual — just the files

```bash
git clone https://github.com/emichy/product-judgment.git
mkdir -p ~/.claude/skills
cp -r product-judgment/skills/* ~/.claude/skills/
```

| Client | Path |
|--------|------|
| Claude Code / Claude Desktop | `~/.claude/skills/` (you) or `.claude/skills/` (commit to the team repo) |
| Cursor | `~/.cursor/skills/` or `.cursor/skills/` |
| Codex | `~/.codex/skills/` or `.codex/skills/` |

Then `/product-judgment` — or just describe the bet.

## Skills

| Skill | Use when |
|-------|----------|
| `product-judgment` | Idea, request, or bet to challenge |
| `prep-customer-interview` | Need a person to talk to, or a call's coming up |
| `review-interview` | How the call went, what you missed |
| `extract-customer-insights` | What the call means for the product |
| `make-it-land` | Internal ask that has to move a decision |

Review coaches you. Extract coaches the bet.

Originally [Lisnloop](https://lisnloop.com) — talk, extract, bet, ship, loop.

MIT · PRs that add hedging get closed.
