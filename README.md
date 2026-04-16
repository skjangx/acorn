# 🌰 Acorn

Small, sharp tools for Claude Code. Growing over time.

This repo is the `acorn` **marketplace** — a catalog that points at plugins. Each plugin lives in its own repository.

---

## Plugins

| Plugin | What it does | Source |
|--------|--------------|--------|
| 🐿️🥜 [**nutshell**](https://github.com/skjangx/nutshell) | Token-efficient compressed output with optional ELI5 overlay for jargon | [`skjangx/nutshell`](https://github.com/skjangx/nutshell) |

---

## Install

**Step 1 — register the marketplace** (once):

```bash
claude plugin marketplace add skjangx/acorn
```

**Step 2 — install any plugin from it:**

```bash
claude plugin install nutshell@acorn
```

Future plugins will install the same way — `claude plugin install <plugin>@acorn`.

---

## About

Acorn is a personal collection of focused Claude Code tools. Each plugin does one thing: token-efficient output, cleaner conversations, lighter context. Future additions lean on a shared naming theme (trees, nuts, seeds) but each stands on its own.

Plugin repos have their own issues, releases, licenses, and contributors. This repo just holds the marketplace manifest.

## License

MIT. Each plugin repo has its own `LICENSE` — check there for plugin-specific terms.
