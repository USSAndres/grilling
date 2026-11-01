# Grilling

A Claude Code skill that interviews you relentlessly about a plan, decision or idea until you and Claude reach a shared understanding.

It maps the work as a design tree, asks one question at a time from the frontier (the decisions whose prerequisites are already settled), offers 3–4 short options with a recommendation first, looks up facts itself, and leaves every decision to you.

## Install

Copy the folders into your skills directory:

```bash
git clone https://github.com/USSAndres/grilling.git
cp -r grilling/grilling grilling/grill-me ~/.claude/skills/
```

- `grilling/` — the skill. Claude invokes it when you ask to be grilled or to stress-test something.
- `grill-me/` — an optional `/grill-me` slash command that calls `grilling`.
