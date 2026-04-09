# Skills Dev

Claude Code marketplace for developer tooling at Humanists UK.

Companion to [skills-plugin](https://github.com/bhahumanists/skills-plugin) (content/comms skills for staff via Cowork). This marketplace provides engineering tools for the development environment.

## Plugins

| Plugin | What it does |
|--------|-------------|
| **php-lsp** | Intelephense with CiviCRM/WordPress stubs and diagnostic tuning |

## Setup

Register this marketplace in `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "skills-dev": {
      "source": {
        "source": "github",
        "repo": "bhahumanists/skills-dev"
      }
    }
  }
}
```

Then install:

```bash
claude plugin install php-lsp@skills-dev
```
