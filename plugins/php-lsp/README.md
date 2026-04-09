# php-lsp

PHP language server (Intelephense) configured for the Humanists UK monorepo.

Replaces the official `php-lsp@claude-plugins-official` plugin with one that includes:

- **API4 stubs** — resolves dynamically-generated CiviCRM entity classes
- **WordPress stubs** — standard WordPress function signatures
- **Diagnostic tuning** — suppresses false positives from CiviCRM trait properties and magic methods
- **File exclusions** — skips wp-admin, wp-includes, vendor test suites, and cache directories

## Installation

Requires Intelephense globally:

```bash
npm install -g intelephense
```

## Configuration

The `.lsp.json` mirrors the project's `.vscode/settings.json` Intelephense config. If you update one, update the other to keep VS Code and Claude Code in sync.
