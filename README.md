# product-judgment

Product judgment for product engineers who own the bet.

Paste a feature request, a transcript, or "who should I talk to." You leave with the bet, who to call, what to ask — and the conviction to defend it.

Customer → software → customer, fast.

Quick install into Claude Code, Claude Desktop, Cursor.

## Skills

| Skill | Use when |
|-------|----------|
| `pressure-test-a-bet` | Idea, request, or bet to challenge |
| `prep-customer-interview` | Need a person to talk to, or a call's coming up |
| `review-interview` | How the call went, what you missed |
| `extract-customer-insights` | What the call means for the product |
| `make-it-land` | Internal ask that has to move a decision |

Not a coach, not a spec writer, no frameworks, no templates. Scrappy skills that put engineers next to their customers.

Judgment, not process — the decisions where there's often no metric to check against.

## Install

### 1. As a plugin

The plugin is how Claude and Cursor keep skills up to date. Install it once, get updates after that.

**Claude Code** — run these one at a time; the first registers the marketplace, the second installs from it:

1. `/plugin marketplace add emichy/product-judgment`
2. `/plugin install product-judgment@product-judgment`

**Claude Desktop / claude.ai** — **Customize → Plugins → Add → Add marketplace → Add from a repository**. Paste `https://github.com/emichy/product-judgment`, **Sync**, then open **Product Judgment** and **Install**.

**Cursor** — **One click from the directory** [https://cursor.directory/plugins/product-judgment](https://cursor.directory/plugins/product-judgment)

Or from inside Cursor: **Customize → Plugins → Add Marketplace → Import from Github**. Paste `https://github.com/emichy/product-judgment`, then install **Product Judgment**.

Updating later: `/plugin marketplace update product-judgment` then `/plugin update product-judgment@product-judgment` in Claude Code; the **Update** button in Claude Desktop and Cursor.

Installed as a plugin, the skills are namespaced — `/product-judgment:pressure-test-a-bet`. Ugly, and that's how Claude plugins work.

### 2. Anyone — one command

Works everywhere, Codex included:

```bash
npx skills add emichy/product-judgment
```

Via [skills.sh](https://skills.sh/emichy/product-judgment). No plugin UI required.

Installed this way the skills aren't namespaced — `/pressure-test-a-bet`.

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

Installed this way the skills aren't namespaced — `/pressure-test-a-bet`.

## Prompting your assistant

Describe the outcome; the right skill loads itself. For example:

- "Pressure-test this: we should build a health dashboard so CSMs can see at-risk accounts before renewal."
- "Which customers or prospects should I talk to about that, and give me some creative questions to ask."
- "Extract some insights from this call." *(paste the transcript)*
- "How can I ask better customer questions?"
- "Help me pitch this to my CEO in three sentences."
- "Help me build conviction in this bet."

Or invoke a skill by name. Either works.

Originally started as [Lisnloop](https://lisnloop.com) — a free agent for product engineers. Now as a set of skills that work with any AI agent.

MIT · PRs that add hedging get closed.
