# Palash Knowledge Worker Plugins

AI agent teams for real-world workflows.

## Install

Add the marketplace:

```bash
claude plugin marketplace add palashjain95/palash-knowledge-worker-plugins
```

Then install any plugin:

```bash
claude plugin install jobhunter@palash-knowledge-worker-plugins
```

## Available Plugins

| Plugin | What it does |
|--------|-------------|
| **[jobhunter](https://github.com/palashjain95/jobhunter)** | AI recruiting team — scores fit, tailors resume, preps interviews, negotiates offers |

## Adding New Plugins

Each plugin lives in its own repo. This marketplace just indexes them. To add a new plugin, add an entry to `.claude-plugin/marketplace.json`.
